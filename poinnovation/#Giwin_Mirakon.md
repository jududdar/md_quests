# Giwin Mirakon

[Giwin Mirakon](/npc/206203) is a level 60 Gnome Warrior that spawns in [Plane of Innovation](/zone/206).l

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

G

i

w

i

n

 

M

i

r

a

k

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

z

e

k

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

G

i

w

i

n

 

M

i

r

a

k

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

H

e

y

 

w

h

a

t

 

a

r

e

 

y

o

u

 

d

o

i

n

g

!

 

 

L

o

o

k

 

a

t

 

t

h

i

s

 

m

e

s

s

 

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

 

c

a

u

s

e

d

.

 

 

R

a

l

l

o

s

 

i

s

 

n

o

t

 

g

o

i

n

g

 

t

o

 

b

e

 

h

a

p

p

y

 

a

b

o

u

t

 

t

h

i

s

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

c

l

_

b

e

h

e

m

o

t

h

 

a

n

d

 

f

l

a

g

s

 

<

 

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

c

l

_

b

e

h

e

m

o

t

h

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

G

i

w

i

n

 

M

i

r

a

k

o

n

 

g

i

v

e

s

 

y

o

u

 

a

 

l

o

o

k

 

o

f

 

d

i

s

b

e

l

i

e

f

 

a

n

d

 

t

h

e

n

 

c

o

n

c

e

r

n

.

 

 

'

Y

o

u

 

d

e

s

t

r

o

y

e

d

 

t

h

e

 

m

a

c

h

i

n

e

?

!

 

 

Y

o

u

 

s

h

o

u

l

d

 

c

o

m

e

 

w

i

t

h

 

m

e

 

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

a

c

t

i

c

s

.

 

 

S

u

r

e

l

y

 

t

h

e

 

Z

e

k

s

 

w

i

l

l

 

w

a

n

t

 

t

o

 

h

o

n

o

r

 

y

o

u

 

i

n

 

y

o

u

r

 

w

a

r

r

i

n

g

 

s

p

i

r

i

t

.

 

 

I

 

w

i

l

l

 

g

o

 

o

n

 

a

h

e

a

d

 

o

f

 

y

o

u

 

t

o

 

p

r

e

p

a

r

e

 

f

o

r

 

y

o

u

r

 

a

r

r

i

v

a

l

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

 

y

o

u

 

c

a

n

 

a

c

c

e

s

s

 

t

h

e

 

P

l

a

n

e

 

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

o

r

t

a

l

 

t

h

a

t

 

t

h

e

 

w

e

a

k

l

i

.

.

 

E

r

 

t

r

a

n

q

u

i

l

 

h

a

v

e

 

o

p

e

n

e

d

 

i

n

 

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

r

a

n

q

u

i

l

i

t

y

.

 

 

I

 

a

n

t

i

c

i

p

a

t

e

 

o

u

r

 

n

e

x

t

 

m

e

e

t

i

n

g

 

o

n

 

t

h

e

 

B

a

t

t

l

e

f

i

e

l

d

s

 

o

f

 

Z

e

k

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

z

e

k

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

z

e

k

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

b

e

h

e

m

o

t

h

 

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

b

e

h

e

m

o

t

h

"

)

;

















