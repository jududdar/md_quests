# A Planar Projection

[A Planar Projection](/npc/200269) is a level 1 Elemental Warrior that spawns in [Torment, the Plane of Pain](/zone/207).

Their primary faction is [KOS](/faction/5017).l

o

c

a

l

 

F

L

A

G

_

L

I

M

I

T

 

=

 

7

2

;







l

o

c

a

l

 

f

l

a

g

s

 

=

 

0

;




l

o

c

a

l

 

r

i

d

,

 

g

i

d

,

 

c

i

d

;







f

u

n

c

t

i

o

n

 

C

l

i

e

n

t

C

a

n

F

l

a

g

(

m

o

b

)




i

f

 

(

 

m

o

b

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

 

c

l

i

e

n

t

 

=

 

m

o

b

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

;







l

o

c

a

l

 

r

a

i

d

 

=

 

c

l

i

e

n

t

:

G

e

t

R

a

i

d

(

)

;




l

o

c

a

l

 

g

r

o

u

p

 

=

 

c

l

i

e

n

t

:

G

e

t

G

r

o

u

p

(

)

;







i

f

 

(

 

r

i

d

 

a

n

d

 

r

a

i

d

.

v

a

l

i

d

 

a

n

d

 

r

a

i

d

:

G

e

t

I

D

(

)

 

=

=

 

r

i

d

 

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




e

l

s

e

i

f

 

(

 

g

i

d

 

a

n

d

 

g

r

o

u

p

.

v

a

l

i

d

 

a

n

d

 

g

r

o

u

p

:

G

e

t

I

D

(

)

 

=

=

 

g

i

d

 

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




e

l

s

e

i

f

 

(

 

c

i

d

 

a

n

d

 

c

l

i

e

n

t

:

G

e

t

I

D

(

)

 

=

=

 

c

i

d

 

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
















#

#

 

S

i

g

n

a

l

s




r

i

d

,

 

g

i

d

,

 

c

i

d

 

=

 

n

i

l

,

 

n

i

l

,

 

n

i

l

;




l

o

c

a

l

 

c

l

i

e

n

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

C

l

i

e

n

t

B

y

I

D

(

e

.

s

i

g

n

a

l

)

;

	







i

f

 

(

 

c

l

i

e

n

t

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







l

o

c

a

l

 

r

a

i

d

 

=

 

c

l

i

e

n

t

:

G

e

t

R

a

i

d

(

)

;




l

o

c

a

l

 

g

r

o

u

p

 

=

 

c

l

i

e

n

t

:

G

e

t

G

r

o

u

p

(

)

;







i

f

 

(

 

r

a

i

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




r

i

d

 

=

 

r

a

i

d

:

G

e

t

I

D

(

)

;




e

l

s

e

i

f

 

(

 

g

r

o

u

p

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




g

i

d

 

=

 

g

r

o

u

p

:

G

e

t

I

D

(

)

;




e

l

s

e




c

i

d

 

=

 

c

l

i

e

n

t

:

G

e

t

I

D

(

)

;







e

q

.

d

e

b

u

g

(

"

F

l

a

g

g

e

r

 

N

P

C

 

w

i

l

l

 

a

c

k

n

o

w

l

e

d

g

e

 

"

.

.

c

l

i

e

n

t

:

G

e

t

N

a

m

e

(

)

.

.

"

'

s

 

r

a

i

d

/

g

r

o

u

p

;

 

R

a

i

d

 

I

D

 

=

=

 

"

.

.

(

r

i

d

 

o

r

 

"

(

n

i

l

)

"

)

.

.

"

;

 

 

G

r

o

u

p

 

I

D

 

=

=

 

"

.

.

(

g

i

d

 

o

r

 

"

(

n

i

l

)

"

)

,

 

1

)

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




f

l

a

g

s

 

=

 

0

;




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

d

e

p

o

p

*

 

f

o

r

 

6

0

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

d

e

p

o

p

"

 

)

 

t

h

e

n




*

*

A

 

P

l

a

n

a

r

 

P

r

o

j

e

c

t

i

o

n

 

d

e

s

p

a

w

n

s

.

*

*



















#

#

 

D

i

a

l

o

g




l

o

c

a

l

 

q

g

l

o

b

a

l

s

 

=

 

e

q

.

g

e

t

_

q

g

l

o

b

a

l

s

(

e

.

o

t

h

e

r

)

;







i

f

 

(

 

C

l

i

e

n

t

C

a

n

F

l

a

g

(

e

.

o

t

h

e

r

)

 

)

 

t

h

e

n







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










i

f

 

(

 

q

g

l

o

b

a

l

s

.

t

y

l

i

s

 

a

n

d

 

q

g

l

o

b

a

l

s

.

t

y

l

i

s

 

=

=

 

"

2

"

 

)

 

t

h

e

n







*

*

M

e

s

s

a

g

e

:

*

*

 

<

s

p

a

n

 

c

l

a

s

s

=

"

t

e

x

t

-

w

a

r

n

i

n

g

"

>

*

T

h

e

 

P

l

a

n

a

r

 

P

r

o

j

e

c

t

i

o

n

'

s

 

t

h

o

u

g

h

t

s

 

e

n

t

e

r

 

y

o

u

r

 

o

w

n

.

 

 

'

Y

o

u

 

h

a

v

e

 

d

o

n

e

 

w

e

l

l

,

 

n

o

w

 

r

e

c

e

i

v

e

 

t

h

e

 

k

n

o

w

l

e

d

g

e

 

t

h

a

t

 

S

a

r

y

r

n

 

o

n

c

e

 

h

e

l

d

!

'

 

 

Y

o

u

 

l

o

o

k

 

d

o

w

n

 

a

t

 

y

o

u

r

 

a

r

m

s

 

t

o

 

s

e

e

 

a

 

s

e

t

 

o

f

 

u

n

i

n

t

e

l

l

i

g

i

b

l

e

 

r

u

n

e

s

 

b

e

i

n

g

 

b

u

r

n

t

 

i

n

t

o

 

y

o

u

r

 

a

r

m

s

.

 

 

T

h

e

 

p

a

i

n

 

i

s

 

t

e

r

r

i

b

l

e

 

a

n

d

 

s

e

a

r

i

n

g

.

 

 

S

u

d

d

e

n

l

y

 

t

h

e

 

s

e

n

s

a

t

i

o

n

 

i

s

 

g

o

n

e

 

a

n

d

 

t

h

e

 

r

u

n

e

s

 

s

l

o

w

l

y

 

f

a

d

e

.

*

<

/

s

p

a

n

>




e

q

.

s

e

t

_

g

l

o

b

a

l

(

"

s

a

r

y

r

n

"

,

 

"

1

"

,

 

5

,

 

"

F

"

)

;




*

*

M

e

s

s

a

g

e

:

*

*

 

<

s

p

a

n

 

c

l

a

s

s

=

"

t

e

x

t

-

w

a

r

n

i

n

g

"

>

*

Y

o

u

 

h

a

v

e

 

r

e

c

e

i

v

e

d

 

a

 

c

h

a

r

a

c

t

e

r

 

f

l

a

g

!

*

<

/

s

p

a

n

>




f

l

a

g

s

 

=

 

f

l

a

g

s

 

+

 

1

;







i

f

 

(

 

q

g

l

o

b

a

l

s

.

c

l

_

s

a

r

y

r

n

 

)

 

t

h

e

n




e

q

.

d

e

l

e

t

e

_

g

l

o

b

a

l

(

"

c

l

_

s

a

r

y

r

n

"

)

;










e

l

s

e

i

f

 

(

 

n

o

t

 

q

g

l

o

b

a

l

s

.

c

l

_

s

a

r

y

r

n

 

 

)

 

t

h

e

n




*

*

M

e

s

s

a

g

e

:

*

*

 

<

s

p

a

n

 

c

l

a

s

s

=

"

t

e

x

t

-

w

a

r

n

i

n

g

"

>

*

T

h

e

 

P

l

a

n

a

r

 

P

r

o

j

e

c

t

i

o

n

 

s

e

e

m

s

 

t

o

 

f

l

i

c

k

e

r

 

i

n

 

a

n

d

 

o

u

t

 

o

f

 

e

x

i

s

t

e

n

c

e

.

 

 

I

t

 

s

e

e

m

s

 

t

o

 

b

e

 

i

m

p

r

e

s

s

e

d

 

a

n

d

 

g

r

a

t

e

f

u

l

 

f

o

r

 

t

h

e

 

d

e

a

t

h

 

o

f

 

S

a

r

y

r

n

.

*

<

/

s

p

a

n

>




e

q

.

s

e

t

_

g

l

o

b

a

l

(

"

c

l

_

s

a

r

y

r

n

"

,

 

"

1

"

,

 

5

,

 

"

F

"

)

;




*

*

M

e

s

s

a

g

e

:

*

*

 

<

s

p

a

n

 

c

l

a

s

s

=

"

t

e

x

t

-

w

a

r

n

i

n

g

"

>

*

Y

o

u

 

h

a

v

e

 

r

e

c

e

i

v

e

d

 

a

 

n

e

w

 

c

h

e

c

k

l

i

s

t

 

f

l

a

g

!

*

<

/

s

p

a

n

>




f

l

a

g

s

 

=

 

f

l

a

g

s

 

+

 

1

;











