# Tylis Newleaf

[Tylis Newleaf](/npc/203373) is a level 55 Wood Elf Warrior that spawns in [Torment, the Plane of Pain](/zone/207).

Their primary faction is [Inhabitants of Tranquility](/faction/1650).l

o

c

a

l

 

K

E

Y

_

I

T

E

M

_

I

D

 

=

 

2

2

9

5

4

;

 







f

u

n

c

t

i

o

n

 

R

a

i

d

H

a

s

K

e

y

(

c

l

i

e

n

t

)




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







i

f

 

(

 

r

a

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

 

m

e

m

b

e

r

;




f

o

r

 

i

 

=

 

0

,

 

7

1

 

d

o




m

e

m

b

e

r

 

=

 

r

a

i

d

:

G

e

t

M

e

m

b

e

r

(

i

)

;







i

f

 

(

 

m

e

m

b

e

r

 

a

n

d

 

m

e

m

b

e

r

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

 

m

e

m

b

e

r

:

K

e

y

R

i

n

g

C

h

e

c

k

(

K

E

Y

_

I

T

E

M

_

I

D

)

 

o

r

 

m

e

m

b

e

r

:

H

a

s

I

t

e

m

(

K

E

Y

_

I

T

E

M

_

I

D

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

r

o

u

p

C

o

u

n

t

(

)

 

>

 

0

 

)

 

t

h

e

n




f

o

r

 

i

 

=

 

0

,

 

5

 

d

o




l

o

c

a

l

 

m

e

m

b

e

r

 

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

M

e

m

b

e

r

(

i

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

;







i

f

 

(

 

m

e

m

b

e

r

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

 

m

e

m

b

e

r

:

K

e

y

R

i

n

g

C

h

e

c

k

(

K

E

Y

_

I

T

E

M

_

I

D

)

 

o

r

 

m

e

m

b

e

r

:

H

a

s

I

t

e

m

(

K

E

Y

_

I

T

E

M

_

I

D

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













e

l

s

e




i

f

 

(

 

c

l

i

e

n

t

:

K

e

y

R

i

n

g

C

h

e

c

k

(

K

E

Y

_

I

T

E

M

_

I

D

)

 

o

r

 

c

l

i

e

n

t

:

H

a

s

I

t

e

m

(

K

E

Y

_

I

T

E

M

_

I

D

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

o

e

s

n

'

t

 

m

o

v

e

,

 

b

u

t

 

s

t

r

u

g

g

l

e

s

 

t

o

 

w

h

i

s

p

e

r

,

 

'

.

.

.

h

e

l

p

 

.

.

.

e

n

d

 

t

h

i

s

 

t

o

r

m

e

n

t

 

.

.

.

w

i

l

l

 

y

o

u

 

c

o

m

e

?

 

 

I

 

c

a

n

 

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

a

i

n

.

.

.

 

i

t

 

m

o

v

e

s

 

i

n

 

t

h

e

 

s

h

a

d

o

w

s

 

o

f

 

m

y

 

m

i

n

d

.

.

.

 

w

i

l

l

 

y

o

u

 

a

s

s

i

s

t

 

m

e

?

'

*







e

l

s

e







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




l

o

c

a

l

 

n

o

f

l

a

g

 

=

 

f

a

l

s

e

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

 

a

s

s

i

s

t

 

y

o

u

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

 

R

a

i

d

H

a

s

K

e

y

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




>

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

 

s

a

y

s

:

*

*

 

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

 

i

f

 

I

 

h

a

v

e

 

e

n

o

u

g

h

 

e

n

e

r

g

y

 

t

o

 

c

h

a

n

n

e

l

 

a

l

l

 

o

f

 

y

o

u

,

 

b

u

t

 

I

 

c

a

n

 

t

r

y

.

 

 

W

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

,

 

I

 

w

i

l

l

 

c

h

a

n

n

e

l

 

y

o

u

 

i

n

t

o

 

m

y

 

p

a

i

n

.




e

l

s

e




n

o

f

l

a

g

 

=

 

t

r

u

e

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

e

 

a

r

e

 

r

e

a

d

y

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

 

R

a

i

d

H

a

s

K

e

y

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

I

n

s

a

n

i

t

y

 

o

f

 

T

y

l

i

s

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

4

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




e

l

s

e




n

o

f

l

a

g

 

=

 

t

r

u

e

;













i

f

 

(

 

n

o

f

l

a

g

 

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

 

s

e

n

s

e

 

t

h

e

 

d

e

s

i

r

e

 

i

n

 

y

o

u

 

t

o

 

h

e

l

p

,

 

b

u

t

 

I

 

d

o

n

'

t

 

k

n

o

w

 

i

f

 

y

o

u

 

p

o

s

s

e

s

s

 

t

h

e

 

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

 

n

e

e

d

e

d

 

t

o

 

r

e

l

e

a

s

e

 

m

e

 

f

r

o

m

 

m

y

 

a

n

g

u

i

s

h

.

 

 

P

l

e

a

s

e

 

s

e

e

k

 

o

u

t

 

m

y

 

c

o

m

p

a

n

i

o

n

 

F

a

h

l

i

a

 

a

n

d

 

s

e

e

 

i

f

 

s

h

e

 

c

a

n

 

o

f

f

e

r

 

y

o

u

 

a

 

w

a

y

 

t

o

 

b

e

t

t

e

r

 

y

o

u

r

s

e

l

f

 

b

e

f

o

r

e

 

u

n

d

e

r

t

a

k

i

n

g

 

t

h

i

s

 

t

a

s

k

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








