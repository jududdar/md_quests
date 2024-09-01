# Rallos Zek 

[Rallos Zek ](/npc/214052) is a level 76 Rallos Zek Warrior that spawns in [Drunder, the Fortress of Zek](/zone/214).l

o

c

a

l

 

C

O

R

P

S

E

_

T

Y

P

E

S

 

=

 

{

 

[

2

1

4

0

0

7

]

 

=

 

1

,

 

[

2

1

4

0

0

8

]

 

=

 

1

,

 

[

2

1

4

0

0

9

]

 

=

 

1

,

 

[

2

1

4

0

1

0

]

 

=

 

1

,

 

[

2

1

4

0

1

1

]

 

=

 

1

 

}

;







f

u

n

c

t

i

o

n

 

G

e

t

C

o

r

p

s

e

(

)




l

o

c

a

l

 

n

p

c

L

i

s

t

 

=

 

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

G

e

t

N

P

C

L

i

s

t

(

)

;







f

o

r

 

n

p

c

 

i

n

 

n

p

c

L

i

s

t

.

e

n

t

r

i

e

s

 

d

o







i

f

 

(

 

n

p

c

.

v

a

l

i

d

 

)

 

t

h

e

n







i

f

 

(

 

C

O

R

P

S

E

_

T

Y

P

E

S

[

n

p

c

:

G

e

t

N

P

C

T

y

p

e

I

D

(

)

]

 

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

 

n

p

c

;



















f

u

n

c

t

i

o

n

 

D

e

p

o

p

C

o

r

p

s

e

s

(

)




l

o

c

a

l

 

n

p

c

L

i

s

t

 

=

 

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

G

e

t

N

P

C

L

i

s

t

(

)

;







f

o

r

 

n

p

c

 

i

n

 

n

p

c

L

i

s

t

.

e

n

t

r

i

e

s

 

d

o







i

f

 

(

 

n

p

c

.

v

a

l

i

d

 

)

 

t

h

e

n







i

f

 

(

 

C

O

R

P

S

E

_

T

Y

P

E

S

[

n

p

c

:

G

e

t

N

P

C

T

y

p

e

I

D

(

)

]

 

)

 

t

h

e

n




n

p

c

:

D

e

p

o

p

(

t

r

u

e

)

;



















f

u

n

c

t

i

o

n

 

G

e

t

W

r

a

i

t

h

(

)




l

o

c

a

l

 

n

p

c

L

i

s

t

 

=

 

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

G

e

t

N

P

C

L

i

s

t

(

)

;







f

o

r

 

n

p

c

 

i

n

 

n

p

c

L

i

s

t

.

e

n

t

r

i

e

s

 

d

o







i

f

 

(

 

n

p

c

.

v

a

l

i

d

 

)

 

t

h

e

n







i

f

 

(

 

n

p

c

:

G

e

t

N

P

C

T

y

p

e

I

D

(

)

 

=

=

 

2

1

4

3

0

5

 

)

 

t

h

e

n

 




l

o

c

a

l

 

s

p

a

w

n

I

d

 

=

 

n

p

c

:

G

e

t

S

p

a

w

n

P

o

i

n

t

I

D

(

)

;




i

f

 

(

 

s

p

a

w

n

I

d

 

=

=

 

3

6

1

1

9

7

 

o

r

 

s

p

a

w

n

I

d

 

=

=

 

3

6

1

2

0

5

 

o

r

 

3

6

1

2

0

5

 

=

=

 

3

6

1

2

1

1

 

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

 

n

p

c

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

c

o

r

p

s

e

s

*

 

f

o

r

 

6

0

 

s

e

c

o

n

d

s
















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

t

i

m

e

r

 

=

=

 

"

c

o

r

p

s

e

s

"

 

)

 

t

h

e

n







l

o

c

a

l

 

r

o

l

l

 

=

 

m

a

t

h

.

r

a

n

d

o

m

(

1

,

1

0

0

)

;




l

o

c

a

l

 

c

o

r

p

s

e

,

 

s

p

a

w

n

;







i

f

 

(

 

r

o

l

l

 

<

 

6

0

 

)

 

t

h

e

n




c

o

r

p

s

e

 

=

 

G

e

t

C

o

r

p

s

e

(

)

;




i

f

 

(

 

c

o

r

p

s

e

 

a

n

d

 

c

o

r

p

s

e

.

v

a

l

i

d

 

)

 

t

h

e

n




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

M

e

s

s

a

g

e

C

l

o

s

e

(

c

o

r

p

s

e

,

 

t

r

u

e

,

 

1

5

0

,

 

0

,

 

"

A

 

c

o

r

p

s

e

 

i

s

 

r

e

n

e

w

e

d

 

b

y

 

t

h

e

 

p

o

w

e

r

 

o

f

 

R

a

l

l

o

s

.

 

 

I

t

 

h

a

s

 

t

a

k

e

n

 

u

p

 

a

r

m

s

 

i

n

 

t

h

e

 

e

t

e

r

n

a

l

 

b

a

t

t

l

e

 

o

n

c

e

 

m

o

r

e

.

"

)

;




s

p

a

w

n

 

=

 

e

q

.

s

p

a

w

n

2

(

e

q

.

C

h

o

o

s

e

R

a

n

d

o

m

(

2

1

4

0

1

5

,

 

2

1

4

0

1

7

,

 

2

1

4

0

2

1

,

 

2

1

4

0

9

0

)

,

 

2

9

,

 

0

,

 

c

o

r

p

s

e

:

G

e

t

X

(

)

,

 

c

o

r

p

s

e

:

G

e

t

Y

(

)

,

 

c

o

r

p

s

e

:

G

e

t

Z

(

)

,

 

0

)

;

 




s

p

a

w

n

:

C

a

s

t

T

o

N

P

C

(

)

:

S

e

t

W

a

y

p

o

i

n

t

P

a

u

s

e

(

)

;




e

q

.

s

e

t

_

t

i

m

e

r

(

"

d

e

p

o

p

"

,

 

3

0

0

0

0

0

,

 

s

p

a

w

n

)

;




c

o

r

p

s

e

:

D

e

p

o

p

(

t

r

u

e

)

;










e

l

s

e

i

f

 

(

 

r

o

l

l

 

<

 

8

5

 

)

 

t

h

e

n




c

o

r

p

s

e

 

=

 

G

e

t

C

o

r

p

s

e

(

)

;




i

f

 

(

 

c

o

r

p

s

e

 

a

n

d

 

c

o

r

p

s

e

.

v

a

l

i

d

 

)

 

t

h

e

n




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

M

e

s

s

a

g

e

C

l

o

s

e

(

c

o

r

p

s

e

,

 

t

r

u

e

,

 

1

5

0

,

 

0

,

 

"

A

 

c

o

r

p

s

e

 

i

s

 

r

e

n

t

 

b

y

 

t

h

e

 

p

o

w

e

r

 

o

f

 

Z

e

k

.

 

 

I

t

 

h

a

s

 

b

e

e

n

 

f

o

u

n

d

 

l

a

c

k

i

n

g

.

"

)

;




s

p

a

w

n

 

=

 

e

q

.

s

p

a

w

n

2

(

2

1

4

0

7

8

,

 

2

9

,

 

0

,

 

c

o

r

p

s

e

:

G

e

t

X

(

)

,

 

c

o

r

p

s

e

:

G

e

t

Y

(

)

,

 

c

o

r

p

s

e

:

G

e

t

Z

(

)

,

 

0

)

;

 




s

p

a

w

n

:

C

a

s

t

T

o

N

P

C

(

)

:

S

e

t

W

a

y

p

o

i

n

t

P

a

u

s

e

(

)

;




e

q

.

s

e

t

_

t

i

m

e

r

(

"

d

e

p

o

p

"

,

 

3

0

0

0

0

0

,

 

s

p

a

w

n

)

;




c

o

r

p

s

e

:

D

e

p

o

p

(

t

r

u

e

)

;







e

l

s

e




c

o

r

p

s

e

 

=

 

G

e

t

W

r

a

i

t

h

(

)

;




i

f

 

(

 

c

o

r

p

s

e

 

a

n

d

 

c

o

r

p

s

e

.

v

a

l

i

d

 

)

 

t

h

e

n




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

M

e

s

s

a

g

e

C

l

o

s

e

(

c

o

r

p

s

e

,

 

t

r

u

e

,

 

1

5

0

,

 

0

,

 

"

A

 

W

a

r

 

W

r

a

i

t

h

 

r

a

i

s

e

s

 

i

t

s

 

h

a

n

d

s

 

a

n

d

 

b

e

g

i

n

s

 

t

o

 

h

o

w

l

.

 

 

T

h

e

 

b

o

d

i

e

s

 

o

f

 

t

h

e

 

f

a

l

l

e

n

 

a

r

e

 

t

o

r

n

 

a

s

u

n

d

e

r

 

a

s

 

t

h

e

 

j

u

d

g

e

m

e

n

t

 

o

f

 

Z

e

k

 

c

o

n

s

u

m

e

s

 

t

h

e

m

.

"

)

;







D

e

p

o

p

C

o

r

p

s

e

s

(

)

;










e

q

.

s

e

t

_

t

i

m

e

r

(

e

.

t

i

m

e

r

,

 

m

a

t

h

.

r

a

n

d

o

m

(

1

5

,

 

1

8

0

)

 

*

 

1

0

0

0

)

;





