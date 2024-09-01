# A Planar Projection

[A Planar Projection](/npc/200269) is a level 1 Elemental Warrior that spawns in [Plane of Disease](/zone/205).

Their primary faction is [KOS](/faction/5017).











l

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

 

*

 

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

 

a

n

d

 

f

l

a

g

s

 

<

=

 

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

f

u

i

r

s

t

e

l

 

)

 

t

h

e

n




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

f

u

i

r

s

t

e

l

 

=

=

 

"

1

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

Y

o

u

 

r

e

c

o

g

n

i

z

e

 

t

h

e

 

s

o

u

n

d

 

o

f

 

t

h

e

 

v

o

i

c

e

 

e

c

h

o

i

n

g

 

i

n

 

y

o

u

r

 

m

i

n

d

 

t

o

 

b

e

 

M

i

l

y

k

 

F

u

i

r

s

t

e

l

'

s

.

 

 

H

e

 

t

e

l

l

s

 

y

o

u

 

b

e

f

o

r

e

 

f

a

d

i

n

g

,

 

'

I

 

b

e

g

 

o

f

 

y

o

u

,

 

r

e

t

u

r

n

 

t

o

 

m

e

 

w

i

t

h

 

t

h

e

 

w

a

r

d

 

t

h

a

t

 

n

o

w

 

e

n

v

e

l

o

p

s

 

y

o

u

r

 

b

o

d

y

.

 

 

T

h

i

s

 

e

t

h

e

r

i

c

 

e

n

e

r

g

y

 

i

s

 

t

h

e

 

o

n

l

y

 

t

h

i

n

g

 

t

h

a

t

 

c

a

n

 

s

t

o

p

 

t

h

i

s

 

p

l

a

g

u

e

 

t

h

a

t

 

h

a

s

 

b

e

e

n

 

p

l

a

c

e

d

 

u

p

o

n

 

m

e

.

'

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

f

u

i

r

s

t

e

l

"

,

 

"

2

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

g

r

u

m

m

u

s

 

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

g

r

u

m

m

u

s

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

g

r

u

m

m

u

s

 

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

 

t

e

l

l

s

 

y

o

u

,

 

'

N

o

w

 

t

h

a

t

 

G

r

u

m

m

u

s

 

h

a

s

 

f

a

l

l

e

n

,

 

y

o

u

 

m

u

s

t

 

p

a

s

s

 

i

n

t

o

 

t

h

e

 

p

l

a

n

e

 

o

f

 

B

e

r

t

o

x

x

u

l

o

u

s

.

 

D

e

e

p

 

i

n

s

i

d

e

 

o

f

 

t

h

i

s

 

c

a

s

t

l

e

 

y

o

u

 

w

i

l

l

 

f

i

n

d

 

a

 

r

o

o

m

 

w

i

t

h

 

a

 

l

a

r

g

e

 

d

e

c

a

y

i

n

g

 

p

i

p

e

.

 

P

u

s

h

 

i

t

 

o

u

t

 

o

f

 

t

h

e

 

w

a

y

 

a

n

d

 

j

u

m

p

 

i

n

t

o

 

t

h

e

 

v

e

r

y

 

p

l

a

g

u

e

 

t

h

a

t

 

i

s

 

B

e

r

t

o

x

x

u

l

o

u

s

'

 

h

o

m

e

.

 

B

e

 

w

a

r

y

 

i

n

 

y

o

u

r

 

t

r

a

v

e

l

s

,

 

f

o

r

 

h

i

s

 

p

e

s

t

i

l

e

n

c

e

 

s

h

a

l

l

 

c

o

n

s

u

m

e

 

y

o

u

.

'

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

g

r

u

m

m

u

s

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

g

r

u

m

m

u

s

 

)

 

t

h

e

n




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

g

r

u

m

m

u

s

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











