# Giwin Mirakon

[Giwin Mirakon](/npc/206038) is a level 60 Gnome Warrior that spawns in [Drunder, the Fortress of Zek](/zone/214).





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




l

o

c

a

l

 

z

e

k

s

 

=

 

t

o

n

u

m

b

e

r

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

)

 

o

r

 

0

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

 

z

e

k

s

 

>

 

1

 

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

W

e

l

l

 

t

h

e

n

,

 

i

t

 

t

o

o

k

 

y

o

u

 

l

o

n

g

 

e

n

o

u

g

h

 

t

o

 

g

e

t

 

h

e

r

e

.

 

 

T

h

e

 

Z

e

k

s

 

h

a

v

e

 

g

r

o

w

n

 

t

i

r

e

d

 

o

f

 

w

a

i

t

i

n

g

 

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

 

 

T

h

e

y

 

h

a

v

e

 

r

e

t

i

r

e

d

 

t

o

 

t

h

e

i

r

 

q

u

a

r

t

e

r

s

.

 

 

I

 

t

h

i

n

k

 

t

h

a

t

 

y

o

u

 

s

h

o

u

l

d

 

s

e

e

k

 

t

h

e

m

 

o

u

t

,

 

t

h

e

y

 

m

u

s

t

 

h

a

v

e

 

a

 

w

a

r

m

 

w

e

l

c

o

m

e

 

f

o

r

 

s

o

m

e

o

n

e

 

w

i

t

h

 

s

u

c

h

 

a

 

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

!

 

 

D

o

 

n

o

t

 

m

i

n

d

 

t

h

e

 

m

i

n

i

o

n

s

 

o

f

 

t

h

i

s

 

r

e

a

l

m

,

 

i

t

 

i

s

 

w

i

t

h

i

n

 

t

h

e

i

r

 

n

a

t

u

r

e

 

t

o

 

c

h

a

l

l

e

n

g

e

 

a

n

y

 

t

h

a

t

 

c

o

m

e

 

w

i

t

h

i

n

 

t

h

e

i

r

 

r

e

a

c

h

.

 

 

P

r

e

s

s

 

o

n

 

a

n

d

 

f

i

n

d

 

t

h

e

 

Z

e

k

s

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

o

 

a

r

e

 

y

o

u

 

t

o

 

t

a

l

k

 

t

o

 

m

e

?

 

 

A

r

e

 

y

o

u

 

a

 

W

a

r

r

i

o

r

 

o

f

 

R

a

l

l

o

s

?

 

 

W

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

 

h

e

r

e

?

!

 

 

M

a

y

b

e

 

y

o

u

 

s

h

o

u

l

d

 

l

e

a

v

e

 

b

e

f

o

r

e

 

y

o

u

 

m

a

k

e

 

m

e

 

a

n

g

r

y

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







l

o

c

a

l

 

i

t

e

m

I

n

s

t

,

 

i

t

e

m

;







f

o

r

 

i

 

=

 

1

,

 

4

 

d

o







i

t

e

m

I

n

s

t

 

=

 

e

.

t

r

a

d

e

[

"

i

t

e

m

"

.

.

i

]

;







i

f

 

(

 

i

t

e

m

I

n

s

t

 

a

n

d

 

i

t

e

m

I

n

s

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




i

t

e

m

 

=

 

i

t

e

m

I

n

s

t

:

G

e

t

I

t

e

m

(

)

;







>

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

n

k

s

 

f

o

r

 

t

h

e

 

"

.

.

i

t

e

m

I

n

s

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

 

S

o

a

n

d

s

o

.







i

f

 

(

 

i

t

e

m

:

N

o

D

r

o

p

(

)

 

=

=

 

2

5

5

 

a

n

d

 

e

.

s

e

l

f

:

C

o

u

n

t

L

o

o

t

(

)

 

<

 

3

0

 

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

R

e

m

o

v

e

I

t

e

m

(

i

t

e

m

I

n

s

t

:

G

e

t

I

D

(

)

)

 




e

.

s

e

l

f

:

A

d

d

I

t

e

m

(

i

t

e

m

I

n

s

t

:

G

e

t

I

D

(

)

,

 

i

t

e

m

I

n

s

t

:

G

e

t

C

h

a

r

g

e

s

(

)

,

 

t

r

u

e

)

;











