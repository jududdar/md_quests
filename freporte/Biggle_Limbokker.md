# Biggle Limbokker

[Biggle Limbokker](/npc/10160) is a level 19 Halfling Rogue that spawns in [East Freeport](/zone/10).

Their primary faction is [Deeppockets](/faction/241).





#

#

 

D

i

a

l

o

g




*

*

Y

o

u

 

s

a

y

:

*

*

 

`

h

a

i

l

`







>

*

*

B

i

g

g

l

e

 

L

i

m

b

o

k

k

e

r

 

s

a

y

s

:

*

*

 

G

o

o

d

 

d

a

y

 

t

o

 

y

o

u

,

 

S

o

a

n

d

s

o

!

 

L

e

a

r

n

 

t

o

 

m

i

n

d

 

y

o

u

r

 

o

w

n

 

b

u

s

i

n

e

s

s

 

i

n

 

t

h

i

s

 

p

l

a

c

e

.

 

I

f

 

a

 

f

i

g

h

t

 

b

r

e

a

k

s

 

o

u

t

,

 

d

o

 

n

o

t

 

g

e

t

 

i

n

 

t

h

e

 

w

a

y

.



















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

 

t

u

r

n

,

 

b

a

r

d

;







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




>

*

*

B

i

g

g

l

e

 

L

i

m

b

o

k

k

e

r

 

s

a

y

s

:

*

*

 

Y

e

s

!

 

S

e

n

d

 

m

o

r

e

 

h

i

g

h

 

e

l

f

 

l

a

d

i

e

s

 

t

o

 

F

r

e

e

p

o

r

t

.




t

u

r

n

 

=

 

t

r

u

e

;




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

 

4

 

)

 

t

h

e

n




>

*

*

B

i

g

g

l

e

 

L

i

m

b

o

k

k

e

r

 

s

a

y

s

:

*

*

 

Q

e

y

n

o

s

 

i

s

 

a

 

g

r

e

a

t

 

c

i

t

y

.

 

T

h

e

i

r

 

t

r

o

o

p

s

 

h

a

v

e

 

a

i

d

e

d

 

R

i

v

e

r

v

a

l

e

 

m

a

n

y

 

t

i

m

e

s

.




t

u

r

n

 

=

 

t

r

u

e

;




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

 

5

 

)

 

t

h

e

n




>

*

*

B

i

g

g

l

e

 

L

i

m

b

o

k

k

e

r

 

s

a

y

s

:

*

*

 

T

h

o

s

e

 

E

r

u

d

i

t

e

s

 

a

r

e

 

n

o

 

f

u

n

 

a

t

 

a

l

l

.




t

u

r

n

 

=

 

t

r

u

e

;




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

 

6

 

)

 

t

h

e

n




>

*

*

B

i

g

g

l

e

 

L

i

m

b

o

k

k

e

r

 

s

a

y

s

:

*

*

 

T

h

a

t

 

v

o

i

c

e

 

m

u

s

t

 

h

a

v

e

 

s

c

a

r

e

d

 

h

i

m

 

a

w

a

y

.




t

u

r

n

 

=

 

t

r

u

e

;




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

 

7

 

)

 

t

h

e

n




>

*

*

B

i

g

g

l

e

 

L

i

m

b

o

k

k

e

r

 

s

a

y

s

:

*

*

 

B

i

g

g

l

e

 

L

i

m

b

o

k

k

e

r

 

f

o

r

 

r

u

l

e

r

 

o

f

 

Q

e

y

n

o

s

!

!

 

A

 

v

o

t

e

 

f

o

r

 

B

i

g

g

l

e

 

i

s

 

a

 

v

o

t

e

 

f

o

r

 

g

r

u

b

,

 

g

r

o

g

 

a

n

d

 

s

o

n

g

.




t

u

r

n

 

=

 

t

r

u

e

;










i

f

 

(

 

t

u

r

n

 

)

 

t

h

e

n




b

a

r

d

 

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

M

o

b

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

1

0

1

4

1

)

;

	

	

	




i

f

 

(

 

n

o

t

 

b

a

r

d

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




b

a

r

d

 

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

M

o

b

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

1

0

1

5

8

)

;

	

	







i

f

 

(

 

n

o

t

 

b

a

r

d

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




b

a

r

d

 

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

M

o

b

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

1

0

1

6

5

)

;

	

	







i

f

 

(

 

b

a

r

d

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

.

s

e

l

f

:

F

a

c

e

T

a

r

g

e

t

(

b

a

r

d

)

;








