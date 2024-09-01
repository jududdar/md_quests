# a spiroc vanquisher

[a spiroc vanquisher](/npc/71009) is a level 58 Aviak Warrior that spawns in [Plane of Sky](/zone/71).

Their primary faction is [KOS](/faction/5017).l

o

c

a

l

 

a

r

r

i

v

e

 

=

 

{

}

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

D

 

=

 

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




a

r

r

i

v

e

[

s

p

a

w

n

I

D

]

 

=

 

t

r

u

e

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

D

 

=

=

 

3

6

4

3

1

1

 

)

 

t

h

e

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

a

l

l

e

r

*

 

f

o

r

 

1

 

s

e

c

o

n

d

s







e

l

s

e

i

f

 

(

 

s

p

a

w

n

I

D

 

=

=

 

3

6

4

3

1

6

 

)

 

t

h

e

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

e

x

p

u

l

s

e

r

*

 

f

o

r

 

1

 

s

e

c

o

n

d

s







e

l

s

e

i

f

 

(

 

s

p

a

w

n

I

D

 

=

=

 

3

6

4

3

2

2

 

)

 

t

h

e

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

a

r

b

i

t

e

r

*

 

f

o

r

 

1

 

s

e

c

o

n

d

s



















#

#

 

S

i

g

n

a

l

s







i

f

 

(

 

e

.

s

i

g

n

a

l

 

=

=

 

1

 

)

 

t

h

e

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

a

r

b

i

t

e

r

*

 

f

o

r

 

1

 

s

e

c

o

n

d

s







e

l

s

e

i

f

 

(

 

e

.

s

i

g

n

a

l

 

=

=

 

2

 

)

 

t

h

e

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

a

l

l

e

r

*

 

f

o

r

 

1

 

s

e

c

o

n

d

s







e

l

s

e

i

f

 

(

 

e

.

s

i

g

n

a

l

 

=

=

 

3

 

)

 

t

h

e

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

e

x

p

u

l

s

e

r

*

 

f

o

r

 

1

 

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

 

o

r

 

e

.

s

e

l

f

:

C

h

a

r

m

e

d

(

)

 

o

r

 

n

o

t

 

a

r

r

i

v

e

[

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

;










l

o

c

a

l

 

e

l

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

;







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

a

r

b

i

t

e

r

"

 

)

 

t

h

e

n




i

f

 

(

 

n

o

t

 

e

l

i

s

t

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

7

1

0

0

8

)

 

)

 

t

h

e

n

 




*

*

S

p

a

w

n

 

N

P

C

 

f

r

o

m

 

s

p

a

w

n

 

g

r

o

u

p

:

*

*

 

 

U

n

k

n

o

w

n

 

N

P

C

 

w

i

t

h

 

i

d

:

 

3

6

4

3

1

5

.

 

a

f

t

e

r

 

1

 

s

e

c

o

n

d

(

s

)










e

l

s

e

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

a

l

l

e

r

"

 

)

 

t

h

e

n




i

f

 

(

 

n

o

t

 

e

l

i

s

t

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

7

1

0

1

5

)

 

)

 

t

h

e

n

 




*

*

S

p

a

w

n

 

N

P

C

 

f

r

o

m

 

s

p

a

w

n

 

g

r

o

u

p

:

*

*

 

 

U

n

k

n

o

w

n

 

N

P

C

 

w

i

t

h

 

i

d

:

 

3

6

4

3

1

0

.

 

a

f

t

e

r

 

1

 

s

e

c

o

n

d

(

s

)










e

l

s

e

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

e

x

p

u

l

s

e

r

"

 

)

 

t

h

e

n




i

f

 

(

 

n

o

t

 

e

l

i

s

t

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

7

1

0

1

1

)

 

)

 

t

h

e

n

 




*

*

S

p

a

w

n

 

N

P

C

 

f

r

o

m

 

s

p

a

w

n

 

g

r

o

u

p

:

*

*

 

 

U

n

k

n

o

w

n

 

N

P

C

 

w

i

t

h

 

i

d

:

 

3

6

4

3

2

1

.

 

a

f

t

e

r

 

1

 

s

e

c

o

n

d

(

s

)













e

q

.

s

t

o

p

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

)

;
















#

#

 

C

o

m

b

a

t




i

f

 

 

a

 

s

p

i

r

o

c

 

v

a

n

q

u

i

s

h

e

r

 

e

n

t

e

r

s

 

c

o

m

b

a

t

 

 

t

h

e

n




a

r

r

i

v

e

[

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

]

 

=

 

f

a

l

s

e

;



















#

#

 

A

r

r

i

v

e

 

a

t

 

W

a

y

p

o

i

n

t

 

S

c

r

i

p

t




a

r

r

i

v

e

[

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

]

 

=

 

t

r

u

e

;


