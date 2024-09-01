# Fahlia Shadyglade

[Fahlia Shadyglade](/npc/203372) is a level 55 Half Elf Warrior that spawns in [Plane of Tranquility](/zone/203).

Their primary faction is [Inhabitants of Tranquility](/faction/1650).l

o

c

a

l

 

R

E

F

U

S

E

_

T

X

T

 

=

 

"

F

a

h

l

i

a

 

S

h

a

d

y

g

l

a

d

e

 

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

 

c

a

n

 

s

e

e

 

t

h

a

t

 

y

o

u

 

m

a

y

 

b

e

 

p

a

s

s

i

o

n

a

t

e

 

t

o

 

h

e

l

p

 

o

t

h

e

r

s

 

b

u

t

 

n

o

w

 

I

 

m

u

s

t

 

a

s

k

 

y

o

u

 

t

o

 

b

e

 

a

b

o

u

t

 

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

.

 

I

 

s

e

n

s

e

 

t

h

a

t

 

i

f

 

y

o

u

 

w

e

r

e

 

t

o

 

t

r

y

 

t

o

 

h

e

l

p

 

y

o

u

 

m

a

y

 

b

e

f

a

l

l

 

t

h

e

 

s

a

m

e

 

f

a

t

e

 

a

s

 

p

o

o

r

 

T

y

l

i

s

.

 

 

P

e

r

h

a

p

s

 

y

o

u

 

s

h

o

u

l

d

 

b

e

c

o

m

e

 

m

o

r

e

 

e

x

p

e

r

i

e

n

c

e

d

 

i

n

 

t

r

a

v

e

l

i

n

g

 

t

h

r

o

u

g

h

 

t

h

e

 

p

l

a

n

e

s

 

b

e

f

o

r

e

 

y

o

u

 

l

e

a

r

n

 

m

o

r

e

 

o

f

 

h

i

s

 

c

o

n

d

i

t

i

o

n

.

'

"

;













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

F

a

h

l

i

a

 

S

h

a

d

y

g

l

a

d

e

 

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

T

h

i

s

 

i

s

 

w

o

n

d

e

r

f

u

l

!

 

I

 

a

m

 

s

o

 

h

a

p

p

y

 

t

h

a

t

 

y

o

u

 

c

o

u

l

d

 

h

e

l

p

 

t

o

 

f

r

e

e

 

T

y

l

i

s

 

f

r

o

m

 

S

a

r

y

r

n

'

s

 

g

r

a

s

p

!

 

 

P

l

e

a

s

e

 

t

r

y

 

n

o

t

 

t

o

 

b

o

t

h

e

r

 

h

i

m

 

t

o

o

 

m

u

c

h

.

 

H

e

 

w

i

l

l

 

n

e

e

d

 

t

i

m

e

 

t

o

 

r

e

c

o

v

e

r

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

l

s

e




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

F

a

h

l

i

a

 

S

h

a

d

y

g

l

a

d

e

 

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

G

r

e

e

t

i

n

g

s

 

t

r

a

v

e

l

e

r

s

.

 

P

l

e

a

s

e

 

e

x

c

u

s

e

 

m

e

 

b

u

t

 

I

 

m

u

s

t

 

a

t

t

e

n

d

 

t

o

 

T

y

l

i

s

 

f

o

r

 

h

i

s

 

c

o

n

d

i

t

i

o

n

 

d

o

e

s

 

n

o

t

 

i

m

p

r

o

v

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

c

o

n

d

i

t

i

o

n

`










i

f

 

(

 

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

h

e

l

i

n

 

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

h

e

l

i

n

 

=

=

 

"

4

"

)

 

a

n

d

 

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

f

u

i

r

s

t

e

l

 

o

r

 

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

 

~

=

 

"

5

"

)

 

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

F

a

h

l

i

a

 

S

h

a

d

y

g

l

a

d

e

 

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

 

u

n

d

e

r

s

t

a

n

d

 

t

h

a

t

 

y

o

u

 

a

r

e

 

p

a

s

s

i

o

n

a

t

e

 

t

o

 

o

u

r

 

c

a

u

s

e

,

 

I

 

h

a

v

e

 

h

e

a

r

d

 

t

h

a

t

 

y

o

u

 

h

a

v

e

 

r

e

c

o

v

e

r

e

d

 

T

h

e

l

i

n

'

s

 

s

a

n

i

t

y

.

 

Y

o

u

 

m

a

y

 

b

e

 

p

o

w

e

r

f

u

l

 

e

n

o

u

g

h

 

t

o

 

e

n

t

e

r

 

i

n

t

o

 

t

h

e

 

d

o

m

a

i

n

 

o

f

 

S

a

r

y

r

n

,

 

b

u

t

 

b

e

f

o

r

e

 

I

 

c

a

n

 

a

s

k

 

y

o

u

 

t

o

 

h

e

l

p

 

T

y

l

i

s

 

p

e

r

h

a

p

s

 

y

o

u

 

s

h

o

u

l

d

 

h

e

l

p

 

o

n

e

 

t

h

a

t

 

i

s

 

i

n

 

m

o

r

e

 

d

i

r

e

 

n

e

e

d

.

 

G

o

 

t

a

l

k

 

t

o

 

A

d

l

e

r

 

F

u

i

r

s

t

e

l

.

 

H

i

s

 

b

r

o

t

h

e

r

 

h

a

s

 

f

a

l

l

e

n

 

u

n

d

e

r

 

t

h

e

 

c

u

r

s

e

 

o

f

 

a

 

g

o

d

 

j

u

s

t

 

l

i

k

e

 

T

h

e

l

i

n

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

l

s

e

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

h

e

l

i

n

 

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

h

e

l

i

n

 

=

=

 

"

4

"

 

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

f

u

i

r

s

t

e

l

 

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

5

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

F

a

h

l

i

a

 

S

h

a

d

y

g

l

a

d

e

 

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

t

 

a

l

l

 

g

o

e

s

 

b

a

c

k

 

t

o

 

w

h

e

n

 

I

 

f

o

u

n

d

 

h

i

m

.

 

I

 

h

a

d

 

j

u

s

t

 

p

u

r

c

h

a

s

e

d

 

a

 

n

e

w

 

f

i

s

h

i

n

g

 

p

o

l

e

 

i

n

 

t

h

e

 

h

o

p

e

s

 

o

f

 

f

i

n

d

i

n

g

 

s

o

m

e

 

t

i

m

e

 

t

o

 

r

e

l

a

x

 

o

n

 

t

h

e

 

s

h

o

r

e

s

 

o

f

 

t

h

e

 

i

s

l

a

n

d

.

 

A

s

 

I

 

w

a

s

 

w

a

l

k

i

n

g

 

o

u

t

 

o

f

 

t

h

e

 

s

h

o

p

,

 

I

 

h

e

a

r

d

 

a

 

d

i

s

t

a

n

t

 

m

o

a

n

.

 

I

 

w

a

l

k

e

d

 

t

o

w

a

r

d

 

t

h

e

 

s

o

u

r

c

e

 

a

n

d

 

f

o

u

n

d

 

T

y

l

i

s

 

l

y

i

n

g

 

b

y

 

t

h

e

 

r

e

f

l

e

c

t

i

n

g

 

p

o

o

l

.

 

T

h

e

 

p

o

o

l

 

w

a

s

 

d

i

f

f

e

r

e

n

t

,

 

t

h

o

u

g

h

.

 

I

t

 

n

o

w

 

h

a

d

 

a

 

s

m

a

l

l

 

[

b

l

a

c

k

 

c

u

b

e

]

 

f

l

o

a

t

i

n

g

 

o

v

e

r

 

i

t

.

 

I

 

t

r

i

e

d

 

t

o

 

w

a

k

e

 

T

y

l

i

s

 

b

u

t

 

w

a

s

 

n

o

t

 

s

u

c

c

e

s

s

f

u

l

.

 

I

 

t

h

e

n

 

b

r

o

u

g

h

t

 

h

i

m

 

h

e

r

e

 

a

n

d

 

h

a

v

e

 

b

e

e

n

 

c

a

r

i

n

g

 

f

o

r

 

h

i

m

 

s

i

n

c

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

l

s

e




e

.

o

t

h

e

r

:

M

e

s

s

a

g

e

(

0

,

 

R

E

F

U

S

E

_

T

X

T

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

b

l

a

c

k

 

c

u

b

e

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

h

e

l

i

n

 

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

h

e

l

i

n

 

=

=

 

"

4

"

 

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

f

u

i

r

s

t

e

l

 

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

5

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

F

a

h

l

i

a

 

S

h

a

d

y

g

l

a

d

e

 

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

o

t

 

l

i

k

e

 

t

h

a

t

 

c

u

b

e

 

a

t

 

a

l

l

.

 

J

u

s

t

 

t

h

i

n

k

i

n

g

 

o

f

 

i

t

 

b

r

i

n

g

s

 

p

a

i

n

 

t

o

 

m

y

 

m

i

n

d

.

 

G

a

z

i

n

g

 

u

p

o

n

 

i

t

 

g

i

v

e

s

 

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

 

o

f

 

b

e

i

n

g

 

s

l

o

w

l

y

 

r

e

n

t

 

a

p

a

r

t

 

a

t

 

e

a

c

h

 

l

i

m

b

.

 

I

 

b

e

l

i

e

v

e

 

t

h

a

t

 

w

h

a

t

e

v

e

r

 

h

a

s

 

f

a

l

l

e

n

 

o

v

e

r

 

T

y

l

i

s

 

i

s

 

r

e

l

a

t

e

d

 

t

o

 

t

h

i

s

 

c

u

r

s

e

d

 

c

u

b

e

.

 

O

t

h

e

r

 

e

l

d

e

r

s

 

c

l

a

i

m

 

t

h

a

t

 

i

t

 

i

s

 

a

 

p

o

r

t

a

l

 

t

h

a

t

 

w

i

l

l

 

l

e

a

d

 

i

n

t

o

 

t

h

e

 

[

P

l

a

n

e

 

o

f

 

T

o

r

m

e

n

t

]

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

l

s

e




e

.

o

t

h

e

r

:

M

e

s

s

a

g

e

(

0

,

 

R

E

F

U

S

E

_

T

X

T

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

p

l

a

n

e

 

o

f

 

t

o

r

m

e

n

t

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

h

e

l

i

n

 

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

h

e

l

i

n

 

=

=

 

"

4

"

 

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

f

u

i

r

s

t

e

l

 

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

5

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

F

a

h

l

i

a

 

S

h

a

d

y

g

l

a

d

e

 

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

t

 

i

s

 

n

o

t

 

a

 

p

l

a

n

e

 

t

h

a

t

 

w

a

s

 

o

r

i

g

i

n

a

l

l

y

 

s

o

u

g

h

t

 

t

o

 

b

e

 

r

e

a

c

h

e

d

 

b

y

 

o

u

r

 

e

l

d

e

r

s

.

 

I

t

 

i

s

 

t

h

e

i

r

 

b

e

l

i

e

f

 

t

h

o

u

g

h

 

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

,

 

t

h

e

 

M

i

s

t

r

e

s

s

 

o

f

 

T

o

r

m

e

n

t

,

 

i

n

t

e

n

d

s

 

t

o

 

b

r

e

e

d

 

h

e

r

 

s

u

f

f

e

r

i

n

g

 

e

v

e

n

 

i

n

t

o

 

t

h

i

s

 

p

r

o

t

e

c

t

e

d

 

p

l

a

n

e

 

o

f

 

Q

u

e

l

l

i

o

u

s

.

 

I

 

w

i

s

h

 

I

 

h

a

d

 

t

h

e

 

s

t

r

e

n

g

t

h

 

t

o

 

g

o

 

i

n

t

o

 

t

h

e

 

P

l

a

n

e

 

o

f

 

T

o

r

m

e

n

t

 

a

n

d

 

f

i

n

d

 

o

u

t

 

e

x

a

c

t

l

y

 

t

h

e

 

n

a

t

u

r

e

 

o

f

 

t

h

e

 

c

u

r

r

e

n

t

 

c

i

r

c

u

m

s

t

a

n

c

e

s

 

t

o

 

h

a

v

e

 

a

f

f

l

i

c

t

e

d

 

T

y

l

i

s

,

 

b

u

t

 

I

 

c

a

n

n

o

t

 

l

e

a

v

e

 

h

i

s

 

s

i

d

e

 

i

n

 

g

o

o

d

 

c

o

n

s

c

i

e

n

c

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

l

s

e




e

.

o

t

h

e

r

:

M

e

s

s

a

g

e

(

0

,

 

R

E

F

U

S

E

_

T

X

T

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

w

i

l

l

 

g

o

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

h

e

l

i

n

 

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

h

e

l

i

n

 

=

=

 

"

4

"

 

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

f

u

i

r

s

t

e

l

 

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

5

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

F

a

h

l

i

a

 

S

h

a

d

y

g

l

a

d

e

 

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

W

o

n

d

e

r

f

u

l

.

 

I

 

d

i

d

 

n

o

t

 

t

h

i

n

k

 

t

h

a

t

 

a

n

 

o

u

t

s

i

d

e

r

 

w

a

s

 

o

n

e

 

t

h

a

t

 

I

 

c

o

u

l

d

 

t

r

u

s

t

 

t

o

 

a

i

d

 

m

e

 

i

n

 

t

h

i

s

.

 

O

n

e

 

n

a

m

e

 

t

h

a

t

 

T

y

l

i

s

 

h

a

s

 

m

e

n

t

i

o

n

e

d

 

i

n

 

a

g

o

n

y

 

i

s

 

t

h

a

t

 

o

f

 

M

a

a

r

e

q

.

 

I

 

d

o

 

n

o

t

 

k

n

o

w

 

w

h

o

m

 

t

h

i

s

 

i

s

,

 

b

u

t

 

h

e

 

m

u

s

t

 

b

e

 

i

n

s

t

r

u

m

e

n

t

a

l

 

i

n

 

T

y

l

i

s

'

 

s

u

f

f

e

r

i

n

g

.

 

Y

o

u

 

m

u

s

t

 

f

i

n

d

 

M

a

a

r

e

q

 

a

n

d

 

d

o

 

w

h

a

t

 

y

o

u

 

m

u

s

t

 

t

o

 

r

e

l

e

a

s

e

 

T

y

l

i

s

 

f

r

o

m

 

t

h

i

s

 

t

o

r

t

u

r

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




e

l

s

e




e

.

o

t

h

e

r

:

M

e

s

s

a

g

e

(

0

,

 

R

E

F

U

S

E

_

T

X

T

)

;








