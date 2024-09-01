# Aten Ha Ra

[Aten Ha Ra](/npc/158436) is a level 66 Akheva Warrior that spawns in [Vex Thal](/zone/158).

Their primary faction is [KOS](/faction/5017).l

o

c

a

l

 

W

A

R

D

E

R

_

T

Y

P

E

S

 

=

 

{

 

1

5

8

4

1

8

,

 

1

5

8

4

0

9

,

 

1

5

8

4

0

5

,

 

1

5

8

3

9

9

,

 

1

5

8

3

9

3

 

}

;







l

o

c

a

l

 

c

h

e

c

k

s

 

=

 

0

;







f

u

n

c

t

i

o

n

 

I

s

W

a

r

d

e

r

U

p

(

)




f

o

r

 

_

,

 

i

d

 

i

n

 

i

p

a

i

r

s

(

W

A

R

D

E

R

_

T

Y

P

E

S

)

 

d

o




i

f

 

(

 

e

q

.

g

e

t

_

e

n

t

i

t

y

_

l

i

s

t

(

)

:

I

s

M

o

b

S

p

a

w

n

e

d

B

y

N

p

c

T

y

p

e

I

D

(

i

d

)

 

)

 

t

h

e

n




r

e

t

u

r

n

 

t

r

u

e

;










r

e

t

u

r

n

 

f

a

l

s

e

;










f

u

n

c

t

i

o

n

 

W

a

r

p

(

m

o

b

)




m

o

b

:

G

M

M

o

v

e

(

1

4

1

2

,

 

0

,

 

2

4

5

.

5

,

 

1

9

5

.

8

)

;




m

o

b

:

B

u

f

f

F

a

d

e

A

l

l

(

)

;




m

o

b

:

W

i

p

e

H

a

t

e

L

i

s

t

(

)

;




c

h

e

c

k

s

 

=

 

0

;
















#

#

 

T

i

m

e

r

(

s

)







i

f

 

(

 

e

.

s

e

l

f

:

G

e

t

Z

(

)

 

<

 

2

2

9

 

o

r

 

e

.

s

e

l

f

:

G

e

t

Z

(

)

 

>

 

2

6

0

 

)

 

t

h

e

n




W

a

r

p

(

e

.

s

e

l

f

)

;




r

e

t

u

r

n

;










i

f

 

(

 

e

.

s

e

l

f

:

I

s

E

n

g

a

g

e

d

(

)

 

)

 

t

h

e

n







i

f

 

(

 

I

s

W

a

r

d

e

r

U

p

(

)

 

a

n

d

 

e

.

s

e

l

f

:

G

e

t

T

a

r

g

e

t

(

)

.

v

a

l

i

d

 

a

n

d

 

e

.

s

e

l

f

:

G

e

t

T

a

r

g

e

t

(

)

:

I

s

C

l

i

e

n

t

(

)

 

a

n

d

 

n

o

t

 

e

.

s

e

l

f

:

G

e

t

T

a

r

g

e

t

(

)

:

C

a

s

t

T

o

C

l

i

e

n

t

(

)

:

G

e

t

G

M

(

)

 

)

 

t

h

e

n




e

.

s

e

l

f

:

C

a

s

t

S

p

e

l

l

(

2

8

5

9

,

 

e

.

s

e

l

f

:

G

e

t

T

a

r

g

e

t

(

)

:

G

e

t

I

D

(

)

)

;

 




r

e

t

u

r

n

;
















i

f

 

(

 

e

.

s

e

l

f

:

G

e

t

T

a

r

g

e

t

(

)

:

I

s

W

a

r

r

i

o

r

C

l

a

s

s

(

)

 

a

n

d

 

e

.

s

e

l

f

:

C

o

m

b

a

t

R

a

n

g

e

(

e

.

s

e

l

f

:

G

e

t

T

a

r

g

e

t

(

)

)

	

a

n

d

 

n

o

t

 

e

.

s

e

l

f

:

C

h

e

c

k

L

o

S

(

e

.

s

e

l

f

:

G

e

t

T

a

r

g

e

t

(

)

)

	

)

 

t

h

e

n







c

h

e

c

k

s

 

=

 

c

h

e

c

k

s

 

+

 

1

;




i

f

 

(

 

c

h

e

c

k

s

 

>

 

3

 

)

 

t

h

e

n




W

a

r

p

(

e

.

s

e

l

f

)

;







e

l

s

e




c

h

e

c

k

s

 

=

 

0

;






















#

#

 

O

n

 

N

P

C

 

S

p

a

w

n




*

*

S

e

t

 

a

 

t

i

m

e

r

*

*

 

n

a

m

e

d

 

*

s

p

l

o

i

t

c

h

e

c

k

*

 

f

o

r

 

5

 

s

e

c

o

n

d

s


