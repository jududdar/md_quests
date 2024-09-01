# Tylis Newleaf

[Tylis Newleaf](/npc/207318) is a level 35 Wood Elf Warrior that spawns in [Torment, the Plane of Pain](/zone/207).l

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

T

y

l

i

s

 

N

e

w

l

e

a

f

 

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

y

l

i

s

 

N

e

w

l

e

a

f

 

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

I

 

m

u

s

t

 

t

h

a

n

k

 

y

o

u

 

f

o

r

 

y

o

u

r

 

k

i

n

d

 

e

f

f

o

r

t

s

 

f

r

i

e

n

d

s

.

 

 

T

h

i

s

 

p

l

a

c

e

 

h

a

s

 

l

a

i

d

 

c

l

a

i

m

 

t

o

 

m

e

 

f

o

r

 

f

a

r

 

t

o

o

 

l

o

n

g

.

 

 

P

l

e

a

s

e

 

t

a

k

e

 

c

a

r

e

 

a

n

d

 

o

f

f

e

r

 

t

h

e

 

d

a

r

k

 

w

e

n

c

h

 

m

y

 

b

e

s

t

.

 

 

I

 

a

m

 

o

f

f

.

.

.

 

a

n

d

 

I

 

s

u

g

g

e

s

t

 

y

o

u

 

n

o

t

 

s

t

r

a

y

 

t

o

 

f

a

r

 

f

r

o

m

 

t

h

a

t

 

r

o

u

t

e

 

y

o

u

r

s

e

l

v

e

s

.

 

 

P

l

e

a

s

e

 

t

e

l

l

 

m

e

 

w

h

e

n

 

y

o

u

 

a

r

e

 

r

e

a

d

y

 

t

o

 

r

e

t

u

r

n

 

a

n

d

 

m

a

y

 

y

o

u

r

 

b

l

a

d

e

s

 

s

t

r

i

k

e

 

t

r

u

e

!

'

*

<

/

s

p

a

n

>







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

 

=

=

 

"

1

"

 

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

t

y

l

i

s

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

k

e

e

p

e

r

 

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

k

e

e

p

e

r

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

k

e

e

p

e

r

 

)

 

t

h

e

n







i

f

 

(

 

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

y

l

i

s

 

N

e

w

l

e

a

f

 

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

I

 

d

o

n

'

t

 

r

e

c

o

g

n

i

z

e

 

y

o

u

,

 

s

t

r

a

n

g

e

r

.

 

T

h

a

n

k

 

y

o

u

 

s

o

 

m

u

c

h

 

f

o

r

 

y

o

u

r

 

k

i

n

d

 

e

f

f

o

r

t

s

.

 

 

T

h

i

s

 

p

l

a

c

e

 

h

a

s

 

c

l

a

i

m

e

d

 

m

e

 

f

o

r

 

f

a

r

 

t

o

o

 

l

o

n

g

.

 

 

I

 

w

i

l

l

 

l

e

a

v

e

 

n

o

w

 

t

h

a

t

 

I

 

h

a

v

e

 

b

e

e

n

 

f

r

e

e

d

 

o

f

 

m

y

 

t

o

r

m

e

n

t

.

 

H

o

w

e

v

e

r

,

 

b

e

f

o

r

e

 

I

 

g

o

,

 

p

l

e

a

s

e

 

t

e

l

l

 

m

e

 

w

h

e

n

 

y

o

u

'

r

e

 

[

r

e

a

d

y

 

t

o

 

r

e

t

u

r

n

]

 

a

n

d

 

I

 

w

i

l

l

 

s

e

n

d

 

y

o

u

 

o

u

t

 

f

i

r

s

t

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

k

e

e

p

e

r

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

r

e

a

d

y

 

t

o

 

r

e

t

u

r

n

`







*

*

T

y

l

i

s

 

N

e

w

l

e

a

f

 

c

a

s

t

s

:

*

*

 

[

T

o

r

m

e

n

t

'

s

 

B

e

c

k

o

n

]

(

/

s

p

e

l

l

/

1

1

3

6

)

 

o

n

 

t

a

r

g

e

t

.





