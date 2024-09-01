# Nitram Anizok

[Nitram Anizok](/npc/206033) is a level 46 Gnome Shopkeeper that spawns in [Plane of Innovation](/zone/206).l

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

 

D

R

A

G

O

N

_

T

Y

P

E

 

=

 

2

0

6

2

0

8

;

 







l

o

c

a

l

 

d

r

a

g

o

n

S

l

a

i

n

 

=

 

f

a

l

s

e

;




l

o

c

a

l

 

w

a

l

k

i

n

g

 

=

 

f

a

l

s

e

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




d

r

a

g

o

n

S

l

a

i

n

 

=

 

f

a

l

s

e

;




w

a

l

k

i

n

g

 

=

 

f

a

l

s

e

;




f

l

a

g

s

 

=

 

0

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




d

r

a

g

o

n

S

l

a

i

n

 

=

 

t

r

u

e

;




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

N

o

Q

u

e

s

t

P

a

u

s

e

(

f

a

l

s

e

)

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

 

D

i

a

l

o

g







i

f

 

(

 

d

r

a

g

o

n

S

l

a

i

n

 

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

N

i

t

r

a

m

 

A

n

i

z

o

k

 

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

h

e

w

 

t

h

a

t

 

w

a

s

 

a

 

c

l

o

s

e

 

o

n

e

!

 

 

I

 

s

h

a

l

l

 

h

a

v

e

 

t

o

 

s

t

u

d

y

 

t

h

e

s

e

 

s

c

h

e

m

a

t

i

c

s

 

a

n

d

 

s

e

e

 

w

h

e

r

e

 

I

 

w

e

n

t

 

w

r

o

n

g

.

 

 

M

a

y

b

e

 

i

f

 

I

 

b

u

i

l

d

 

a

 

n

e

w

 

o

n

e

 

t

h

a

t

 

u

s

e

s

 

t

h

e

 

c

o

r

r

e

c

t

 

k

i

n

d

 

o

f

 

p

o

w

e

r

 

s

o

u

r

c

e

 

i

t

 

w

o

u

l

d

 

w

o

r

k

 

b

e

t

t

e

r

!

 

 

A

n

y

h

o

w

,

 

w

h

y

 

d

o

n

'

t

 

y

o

u

 

s

t

o

p

 

t

h

e

s

e

 

b

e

a

s

t

s

 

a

t

 

t

h

e

 

s

o

u

r

c

e

?

 

 

I

f

 

y

o

u

 

g

o

 

u

p

 

t

o

 

t

h

e

 

m

a

i

n

 

f

a

c

t

o

r

y

 

d

o

o

r

 

a

n

d

 

t

w

i

s

t

 

t

h

e

 

v

e

r

y

 

b

o

t

t

o

m

 

r

i

v

e

t

 

o

f

 

t

h

e

 

i

c

o

n

 

t

h

r

e

e

 

t

i

m

e

s

 

t

o

 

t

h

e

 

r

i

g

h

t

,

 

i

t

 

w

i

l

l

 

o

p

e

n

.

 

 

I

 

d

o

u

b

t

 

t

h

e

y

 

h

a

v

e

 

c

h

a

n

g

e

d

 

h

o

w

 

t

h

i

s

 

w

o

r

k

s

.

 

 

G

o

o

d

 

l

u

c

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

p

o

i

_

d

o

o

r

 

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

p

o

i

_

d

o

o

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

 

w

a

l

k

i

n

g

 

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







>

*

*

N

i

t

r

a

m

 

A

n

i

z

o

k

 

s

a

y

s

:

*

*

 

O

h

 

m

y

 

h

e

l

l

o

!

 

 

I

t

 

h

a

s

 

b

e

e

n

 

s

u

c

h

 

a

 

l

o

n

g

 

t

i

m

e

 

s

i

n

c

e

 

I

 

h

a

v

e

 

h

a

d

 

v

i

s

i

t

o

r

s

.

 

 

H

a

v

e

 

y

o

u

 

c

o

m

e

 

t

o

 

l

e

a

r

n

 

o

f

 

[

a

d

v

a

n

c

e

d

 

t

i

n

k

e

r

i

n

g

]

 

a

s

 

w

e

l

l

?







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

a

d

v

a

n

c

e

d

 

t

i

n

k

e

r

i

n

g

`







>

*

*

N

i

t

r

a

m

 

A

n

i

z

o

k

 

s

a

y

s

:

*

*

 

A

y

e

,

 

I

 

a

d

v

a

n

c

e

d

 

t

o

 

t

h

i

s

 

p

l

a

n

e

 

d

u

e

 

t

o

 

m

y

 

w

o

r

k

 

o

n

 

t

i

n

k

e

r

i

n

g

 

b

a

c

k

 

i

n

 

A

k

`

A

n

o

n

.

 

 

A

 

g

r

a

n

d

 

c

i

t

y

 

i

t

 

i

s

,

 

b

u

t

 

m

y

 

a

b

i

l

i

t

i

e

s

 

w

e

r

e

 

c

o

m

p

r

o

m

i

s

e

d

 

w

i

t

h

 

t

h

e

 

m

a

t

e

r

i

a

l

s

 

I

 

h

a

d

 

t

o

 

w

o

r

k

 

w

i

t

h

 

t

h

e

r

e

.

 

 

M

y

 

b

o

d

y

 

a

n

d

 

s

o

u

l

 

h

a

s

 

c

o

m

e

 

t

o

 

r

e

s

t

 

h

e

r

e

,

 

f

o

r

e

v

e

r

 

c

o

m

i

n

g

 

u

p

 

w

i

t

h

 

n

e

w

 

i

d

e

a

s

.

 

 

Y

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

 

a

w

a

r

e

 

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

 

t

h

i

s

 

p

l

a

n

e

 

i

s

 

n

o

t

 

h

o

w

 

i

t

 

w

a

s

 

w

h

e

n

 

I

 

a

r

r

i

v

e

d

.

 

 

M

u

c

h

 

[

c

o

n

s

t

r

u

c

t

i

o

n

]

 

h

a

s

 

t

a

k

e

n

 

p

l

a

c

e

.







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

s

t

r

u

c

t

i

o

n

`







>

*

*

N

i

t

r

a

m

 

A

n

i

z

o

k

 

s

a

y

s

:

*

*

 

W

h

e

n

 

I

 

f

i

r

s

t

 

a

r

r

i

v

e

d

 

I

 

s

t

a

r

t

e

d

 

c

r

e

a

t

i

n

g

 

s

m

a

l

l

e

r

 

t

h

i

n

g

s

.

 

 

A

s

 

t

i

m

e

 

w

e

n

t

 

o

n

 

m

y

 

i

n

v

e

n

t

i

o

n

s

 

b

e

c

a

m

e

 

m

o

r

e

 

a

n

d

 

m

o

r

e

 

f

o

c

u

s

e

d

 

a

n

d

 

i

m

p

r

e

s

s

i

v

e

.

 

 

I

 

s

t

a

r

t

e

d

 

b

u

i

l

d

i

n

g

 

s

t

e

a

m

 

p

o

w

e

r

e

d

 

c

l

o

c

k

w

o

r

k

 

t

o

 

h

e

l

p

 

m

e

 

g

a

t

h

e

r

 

m

a

t

e

r

i

a

l

s

.

 

I

 

h

a

d

 

g

o

n

e

 

t

o

o

 

f

a

r

 

g

i

v

i

n

g

 

t

h

e

m

 

t

h

e

 

a

b

i

l

i

t

y

 

t

o

 

l

e

a

r

n

 

a

n

d

 

w

i

t

h

 

a

 

b

u

i

l

t

 

i

n

 

d

e

s

i

r

e

 

o

f

 

s

e

l

f

 

p

e

r

p

e

t

u

a

t

i

o

n

.

 

 

T

h

e

y

 

b

e

g

a

n

 

t

o

 

i

n

t

e

g

r

a

t

e

 

t

h

e

m

s

e

l

v

e

s

 

w

i

t

h

 

t

h

e

 

c

l

o

c

k

w

o

r

k

 

t

h

a

t

 

a

l

r

e

a

d

y

 

e

x

i

s

t

e

d

 

w

i

t

h

i

n

 

t

h

e

 

f

a

c

t

o

r

y

 

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

 

s

e

e

 

i

f

 

y

o

u

 

s

t

e

p

 

o

u

t

s

i

d

e

.

 

 

I

 

o

n

c

e

 

w

o

r

k

e

d

 

w

i

t

h

i

n

 

t

h

e

 

f

a

c

t

o

r

y

 

w

i

t

h

 

a

 

k

i

n

d

 

a

n

d

 

f

a

i

r

 

g

n

o

m

e

,

 

M

e

l

d

r

a

t

h

.

 

 

N

o

w

 

t

h

a

t

 

h

e

 

h

a

s

 

g

o

n

e

 

m

i

s

s

i

n

g

 

t

h

e

 

c

l

o

c

k

w

o

r

k

s

 

s

e

e

m

 

t

o

 

b

e

 

w

o

r

k

i

n

g

 

t

o

w

a

r

d

s

 

a

 

m

o

r

e

 

d

e

v

i

o

u

s

 

g

o

a

l

.

 

 

T

h

e

 

c

l

o

c

k

w

o

r

k

 

o

u

t

 

h

e

r

e

 

i

n

 

t

h

e

 

j

u

n

k

y

a

r

d

 

h

a

v

e

 

b

e

e

n

 

d

i

s

c

a

r

d

e

d

 

d

u

e

 

t

o

 

t

h

e

i

r

 

m

a

l

f

u

n

c

t

i

o

n

 

o

r

 

r

e

p

l

a

c

e

m

e

n

t

 

b

y

 

a

 

m

o

r

e

 

e

f

f

i

c

i

e

n

t

 

s

e

r

i

e

s

.

 

 

N

e

e

d

l

e

s

s

 

t

o

 

s

a

y

 

t

h

e

i

r

 

[

i

n

s

t

i

n

c

t

 

f

o

r

 

s

u

r

v

i

v

a

l

]

 

h

a

s

 

n

o

t

 

b

e

e

n

 

l

o

s

t

.







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

i

n

s

t

i

n

c

t

 

f

o

r

 

s

u

r

v

i

v

a

l

`







>

*

*

N

i

t

r

a

m

 

A

n

i

z

o

k

 

s

a

y

s

:

*

*

 

T

h

e

 

c

l

o

c

k

w

o

r

k

 

h

a

v

e

 

b

e

c

o

m

e

 

i

n

c

r

e

a

s

i

n

g

l

y

 

a

g

g

r

e

s

s

i

v

e

 

b

e

c

a

u

s

e

 

o

f

 

t

h

e

i

r

 

d

e

s

p

e

r

a

t

i

o

n

 

f

o

r

 

s

p

a

r

e

 

p

a

r

t

s

.

 

 

I

 

h

a

v

e

 

t

o

 

d

e

f

e

n

d

 

m

y

s

e

l

f

 

a

n

y

t

i

m

e

 

I

 

h

e

a

d

 

o

u

t

 

t

o

 

f

i

n

d

 

p

a

r

t

s

 

f

o

r

 

m

y

 

t

i

n

k

e

r

i

n

g

.

 

 

I

 

f

e

a

r

 

f

o

r

 

m

y

 

s

a

f

e

t

y

 

w

i

t

h

 

w

h

a

t

 

i

s

 

b

e

i

n

g

 

b

u

i

l

t

 

i

n

 

t

h

e

 

f

a

c

t

o

r

y

.

 

 

I

 

h

a

v

e

 

s

t

a

r

t

e

d

 

t

o

 

b

u

i

l

d

 

m

y

s

e

l

f

 

m

y

 

o

w

n

 

m

e

a

n

s

 

o

f

 

d

e

f

e

n

s

e

.

 

 

I

t

 

i

s

 

n

e

a

r

l

y

 

c

o

m

p

l

e

t

e

d

 

b

u

t

 

I

 

n

e

e

d

 

a

n

 

o

d

d

 

c

o

m

b

i

n

a

t

i

o

n

 

o

f

 

b

a

t

t

e

r

i

e

s

 

t

o

 

s

t

a

r

t

 

i

t

 

u

p

.

 

 

I

 

s

h

o

u

l

d

 

h

a

v

e

 

p

l

a

n

n

e

d

 

m

o

r

e

 

c

a

r

e

f

u

l

l

y

 

f

o

r

 

i

t

 

t

o

 

u

s

e

 

s

i

m

p

l

e

 

m

a

n

a

 

b

a

t

t

e

r

i

e

s

.







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

m

b

i

n

a

t

i

o

n

 

o

f

 

b

a

t

t

e

r

i

e

s

`







>

*

*

N

i

t

r

a

m

 

A

n

i

z

o

k

 

s

a

y

s

:

*

*

 

W

e

l

l

 

y

o

u

 

s

e

e

 

w

h

e

n

 

I

 

w

a

s

 

b

a

c

k

 

h

o

m

e

 

i

t

 

w

a

s

 

c

o

m

m

o

n

 

f

o

r

 

m

e

 

t

o

 

u

s

e

 

a

 

m

y

c

o

l

o

g

i

c

a

l

 

s

p

o

r

e

 

e

x

t

r

i

c

a

t

e

-

k

i

n

e

t

o

c

o

n

v

e

r

t

o

r

 

t

o

 

p

o

w

e

r

 

m

y

 

d

e

v

i

c

e

s

.

 

 

I

 

s

t

a

r

t

e

d

 

p

l

a

n

n

i

n

g

 

m

y

 

d

e

f

e

n

s

e

 

t

o

 

u

s

e

 

t

h

i

s

 

a

s

 

a

 

p

o

w

e

r

 

s

o

u

r

c

e

 

o

u

t

 

o

f

 

s

h

e

e

r

 

h

a

b

i

t

.

 

 

H

e

r

e

 

i

n

 

t

h

i

s

 

d

e

s

o

l

a

t

i

o

n

 

t

h

e

 

m

u

s

h

r

o

o

m

s

 

t

h

a

t

 

w

e

r

e

 

g

r

o

w

n

 

b

a

c

k

 

h

o

m

e

 

d

o

 

n

o

t

 

e

x

i

s

t

.

 

 

I

 

a

m

 

g

o

i

n

g

 

t

o

 

h

a

v

e

 

t

o

 

r

i

g

 

s

o

m

e

t

h

i

n

g

 

f

r

o

m

 

s

p

a

r

e

 

p

a

r

t

s

.

 

 

I

t

 

i

s

 

t

a

k

i

n

g

 

a

 

l

o

n

g

 

t

i

m

e

 

w

i

t

h

 

m

y

 

h

a

v

i

n

g

 

t

o

 

s

e

a

r

c

h

 

t

h

e

 

j

u

n

k

y

a

r

d

 

s

m

a

l

l

 

p

o

r

t

i

o

n

s

 

a

t

 

a

 

t

i

m

e

 

d

u

e

 

t

o

 

t

h

e

 

c

l

o

c

k

w

o

r

k

s

.

 

 

W

o

u

l

d

 

y

o

u

 

h

e

l

p

 

m

e

 

i

n

 

[

c

o

l

l

e

c

t

i

n

g

 

m

a

t

e

r

i

a

l

s

]

?







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

l

l

e

c

t

i

n

g

 

m

a

t

e

r

i

a

l

s

`







>

*

N

i

t

r

a

m

 

A

n

i

z

o

k

 

p

e

e

r

s

 

o

v

e

r

 

s

o

m

e

 

s

c

h

e

m

a

t

i

c

s

 

l

a

y

i

n

g

 

o

n

 

a

 

t

a

b

l

e

 

n

e

x

t

 

t

o

 

h

i

m

.

 

'

L

e

t

 

u

s

 

s

e

e

 

h

e

r

e

.

 

 

I

 

h

a

v

e

 

s

o

m

e

 

o

f

 

t

h

e

 

b

a

s

e

 

p

a

r

t

s

 

f

o

r

 

t

h

e

 

p

o

w

e

r

 

s

o

u

r

c

e

.

 

 

I

f

 

y

o

u

 

c

o

u

l

d

 

c

o

l

l

e

c

t

 

a

 

c

o

p

p

e

r

 

n

o

d

e

,

 

a

 

b

u

n

d

l

e

 

o

f

 

s

u

p

e

r

 

c

o

n

d

u

c

t

i

v

e

 

w

i

r

e

s

,

 

a

n

d

 

a

n

 

i

n

t

a

c

t

 

p

o

w

e

r

 

c

e

l

l

 

I

 

c

o

u

l

d

 

p

o

w

e

r

 

u

p

 

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

.

 

 

G

o

o

d

 

l

u

c

k

 

t

o

 

y

o

u

 

S

o

a

n

d

s

o

,

 

I

 

h

o

p

e

 

t

h

a

t

 

w

e

 

c

a

n

 

w

o

r

k

 

t

o

g

e

t

h

e

r

 

o

n

 

t

h

i

s

.

'

*






















#

#

 

T

u

r

n

-

I

n

s










i

f

 

(

 

n

o

t

 

w

a

l

k

i

n

g

 

a

n

d

 

 

*

*

Y

o

u

 

t

u

r

n

 

i

n

:

*

*

 

 

 

<

i

m

g

 

s

t

y

l

e

=

"

b

a

c

k

g

r

o

u

n

d

:

u

r

l

(

/

s

t

a

t

i

c

/

i

c

o

n

s

/

b

l

a

n

k

_

s

l

o

t

.

g

i

f

)

;

w

i

d

t

h

:

2

0

p

x

;

h

e

i

g

h

t

:

2

0

p

x

;

"

 

s

r

c

=

"

/

s

t

a

t

i

c

/

i

c

o

n

s

/

i

t

e

m

_

1

1

0

1

.

p

n

g

"

 

a

l

t

=

"

"

 

/

>

 

<

a




 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

h

r

e

f

=

"

/

i

t

e

m

/

9

2

9

5

"

 

d

a

t

a

-

u

r

l

=

"

9

2

9

5

"

 

c

l

a

s

s

=

"

t

o

o

l

t

i

p

-

l

i

n

k

 

l

i

n

k

"

>

C

o

p

p

e

r

 

N

o

d

e

<

/

a

>

,

 

 

<

i

m

g

 

s

t

y

l

e

=

"

b

a

c

k

g

r

o

u

n

d

:

u

r

l

(

/

s

t

a

t

i

c

/

i

c

o

n

s

/

b

l

a

n

k

_

s

l

o

t

.

g

i

f

)

;

w

i

d

t

h

:

2

0

p

x

;

h

e

i

g

h

t

:

2

0

p

x

;

"

 

s

r

c

=

"

/

s

t

a

t

i

c

/

i

c

o

n

s

/

i

t

e

m

_

1

1

4

0

.

p

n

g

"

 

a

l

t

=

"

"

 

/

>

 

<

a




 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

h

r

e

f

=

"

/

i

t

e

m

/

9

4

2

6

"

 

d

a

t

a

-

u

r

l

=

"

9

4

2

6

"

 

c

l

a

s

s

=

"

t

o

o

l

t

i

p

-

l

i

n

k

 

l

i

n

k

"

>

B

u

n

d

l

e

 

o

f

 

S

u

p

e

r

 

C

o

n

d

u

c

t

i

v

e

 

W

i

r

e

s

<

/

a

>

,

 

 

<

i

m

g

 

s

t

y

l

e

=

"

b

a

c

k

g

r

o

u

n

d

:

u

r

l

(

/

s

t

a

t

i

c

/

i

c

o

n

s

/

b

l

a

n

k

_

s

l

o

t

.

g

i

f

)

;

w

i

d

t

h

:

2

0

p

x

;

h

e

i

g

h

t

:

2

0

p

x

;

"

 

s

r

c

=

"

/

s

t

a

t

i

c

/

i

c

o

n

s

/

i

t

e

m

_

1

1

4

4

.

p

n

g

"

 

a

l

t

=

"

"

 

/

>

 

<

a




 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

h

r

e

f

=

"

/

i

t

e

m

/

9

4

3

4

"

 

d

a

t

a

-

u

r

l

=

"

9

4

3

4

"

 

c

l

a

s

s

=

"

t

o

o

l

t

i

p

-

l

i

n

k

 

l

i

n

k

"

>

I

n

t

a

c

t

 

P

o

w

e

r

 

C

e

l

l

<

/

a

>

 

 

)

 

t

h

e

n




>

*

*

N

i

t

r

a

m

 

A

n

i

z

o

k

 

s

a

y

s

:

*

*

 

E

x

c

e

l

l

e

n

t

!

 

 

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

,

 

p

l

e

a

s

e

 

f

o

l

l

o

w

 

m

e

!

 

 

I

 

w

i

l

l

 

s

h

o

w

 

y

o

u

 

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

 

m

y

 

g

r

e

a

t

e

s

t

 

i

n

v

e

n

t

i

o

n

.




w

a

l

k

i

n

g

 

=

 

t

r

u

e

;




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

N

o

Q

u

e

s

t

P

a

u

s

e

(

t

r

u

e

)

;

 




e

.

s

e

l

f

:

A

s

s

i

g

n

W

a

y

p

o

i

n

t

s

(

2

2

)

;




e

.

s

e

l

f

:

S

e

t

N

P

C

F

a

c

t

i

o

n

I

D

(

1

0

0

6

)

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

 

3

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










*

*

T

h

i

s

 

N

P

C

 

*

s

h

o

u

l

d

*

 

r

e

t

u

r

n

 

i

n

c

o

r

r

e

c

t

 

i

t

e

m

s

 

g

i

v

e

n

.

*

*




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







i

f

 

(

 

e

.

w

p

 

=

=

 

2

0

 

)

 

t

h

e

n




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

D

R

A

G

O

N

_

T

Y

P

E

,

 

0

,

 

0

,

 

-

7

1

1

,

 

1

5

8

3

,

 

-

4

5

,

 

1

2

8

)

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

w

p

 

=

=

 

2

7

 

)

 

t

h

e

n




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

D

R

A

G

O

N

_

T

Y

P

E

)

 

)

 

t

h

e

n




>

*

N

i

t

r

a

m

 

A

n

i

z

o

k

 

p

l

a

c

e

s

 

t

h

e

 

p

o

w

e

r

 

u

n

i

t

 

r

i

g

h

t

 

i

n

t

o

 

t

h

e

 

c

h

e

s

t

 

o

f

 

t

h

e

 

h

u

g

e

 

m

e

t

a

l

l

i

c

 

b

e

a

s

t

.

 

 

I

t

 

r

o

a

r

s

 

t

o

 

l

i

f

e

 

a

s

 

s

t

e

a

m

 

b

e

g

i

n

s

 

p

o

u

r

i

n

g

 

o

u

t

 

o

f

 

i

t

s

 

h

u

g

e

 

g

a

p

i

n

g

 

m

a

w

.

 

 

S

u

d

d

e

n

l

y

 

i

t

 

b

e

g

i

n

s

 

t

o

 

a

t

t

a

c

k

!

 

 

'

M

a

l

f

u

n

c

t

i

o

n

!

 

 

T

h

e

r

e

 

i

s

 

a

n

 

e

r

r

o

r

 

i

n

 

i

t

s

 

r

e

c

o

g

n

i

z

a

t

i

o

n

 

p

r

o

c

e

s

s

!

 

 

H

e

l

p

 

m

e

 

t

o

 

s

t

o

p

 

i

t

 

b

e

f

o

r

e

 

i

t

 

d

e

s

t

r

o

y

s

 

u

s

 

a

l

l

!

'

*




e

q

.

s

i

g

n

a

l

(

D

R

A

G

O

N

_

T

Y

P

E

,

 

1

)

;




e

l

s

e




*

*

N

i

t

r

a

m

 

A

n

i

z

o

k

 

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

N

i

t

r

a

m

 

A

n

i

z

o

k

 

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





