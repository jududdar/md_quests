# Cytodl Krish

[Cytodl Krish](/npc/5005) is a level 25 Dark Elf Shadow Knight that spawns in [Highpass Hold](/zone/5).

Their primary faction is [The Dead](/faction/239).





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

C

y

t

o

d

l

 

K

r

i

s

h

 

s

a

y

s

:

*

*

 

W

h

a

t

 

d

o

 

y

o

u

 

w

a

n

t

?

 

I

 

h

a

v

e

 

n

o

 

r

e

a

s

o

n

 

t

o

 

w

a

s

t

e

 

m

y

 

t

i

m

e

 

w

i

t

h

 

t

h

e

 

l

i

k

e

s

 

o

f

 

y

o

u

!




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

h

e

r

e

`







>

*

*

C

y

t

o

d

l

 

K

r

i

s

h

 

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

r

e

 

h

a

v

e

 

b

e

e

n

 

r

e

p

o

r

t

s

 

o

f

 

m

u

r

d

e

r

s

 

w

i

t

h

i

n

 

H

i

g

h

p

a

s

s

,

 

m

u

r

d

e

r

s

 

i

n

 

w

h

i

c

h

 

t

h

e

 

v

i

c

t

i

m

s

 

w

e

r

e

 

d

r

a

i

n

e

d

 

o

f

 

e

v

e

r

y

 

i

o

t

a

 

o

f

 

b

l

o

o

d

.

 

I

 

w

a

s

 

s

e

n

t

 

h

e

r

e

 

b

y

 

m

y

 

[

g

u

i

l

d

 

m

a

s

t

e

r

]

 

t

o

 

i

n

v

e

s

t

i

g

a

t

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

g

u

i

l

d

 

m

a

s

t

e

r

`







i

f

(

 

*

*

F

a

c

t

i

o

n

 

i

s

*

*

 

>

=

 

A

m

i

a

b

l

e

)

 

t

h

e

n

 




>

*

*

C

y

t

o

d

l

 

K

r

i

s

h

 

s

a

y

s

:

*

*

 

I

 

w

a

s

 

s

e

n

t

 

h

e

r

e

 

b

y

 

N

o

x

h

i

l

 

V

'

S

e

k

 

o

f

 

t

h

e

 

D

e

a

d

.

 

W

e

 

a

r

e

 

t

h

e

 

n

e

c

r

o

m

a

n

c

e

r

s

 

a

n

d

 

s

h

a

d

o

w

k

n

i

g

h

t

s

 

o

f

 

N

e

r

i

a

k

.




e

l

s

e

i

f

(

 

*

*

F

a

c

t

i

o

n

 

i

s

*

*

 

=

=

 

I

n

d

i

f

f

e

r

e

n

t

)

 

t

h

e

n




>

*

*

C

y

t

o

d

l

 

K

r

i

s

h

 

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

 

y

o

u

 

l

e

a

r

n

 

t

o

 

s

e

r

v

e

 

t

h

e

 

D

e

a

d

,

 

t

h

e

n

 

I

 

w

i

l

l

 

f

i

n

d

 

t

h

e

 

t

i

m

e

 

t

o

 

s

p

e

a

k

 

o

f

 

s

u

c

h

 

t

h

i

n

g

s

.




e

l

s

e




>

*

*

C

y

t

o

d

l

 

K

r

i

s

h

 

s

a

y

s

:

*

*

 

H

o

w

 

d

a

r

e

 

y

o

u

 

e

n

t

e

r

 

m

y

 

p

r

e

s

e

n

c

e

?

!

 

 

I

n

 

t

h

e

 

n

a

m

e

 

o

f

 

t

h

e

 

D

e

a

d

 

I

 

s

h

o

u

l

d

 

s

t

r

i

k

e

 

y

o

u

 

d

o

w

n

!






















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

t

i

m

e

c

h

e

c

k

*

 

f

o

r

 

6

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

t

i

m

e

c

h

e

c

k

"

 

a

n

d

 

n

o

t

 

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







l

o

c

a

l

 

z

o

n

e

T

i

m

e

 

=

 

e

q

.

g

e

t

_

z

o

n

e

_

t

i

m

e

(

)

[

"

z

o

n

e

_

h

o

u

r

"

]

;







i

f

 

(

 

z

o

n

e

T

i

m

e

 

>

 

1

8

 

o

r

 

z

o

n

e

T

i

m

e

 

<

 

8

 

)

 

t

h

e

n




*

*

C

y

t

o

d

l

 

K

r

i

s

h

 

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

 

O

n

 

N

P

C

 

D

e

a

t

h




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

3

6

2

6

9

.

 

a

f

t

e

r

 

1

2

0

0

 

s

e

c

o

n

d

(

s

)


