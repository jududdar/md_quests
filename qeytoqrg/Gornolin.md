# Gornolin

[Gornolin](/npc/4003) is a level 20 Human Shopkeeper that spawns in [Qeynos Hills](/zone/4).

Their primary faction is [Merchants of Highpass](/faction/331).





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

n

o

s

e

l

l

*

 

f

o

r

 

1

 

s

e

c

o

n

d

s




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

p

i

c

k

_

u

p

*

 

f

o

r

 

2

 

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

n

o

s

e

l

l

"

)

 

t

h

e

n




*

*

S

t

o

p

 

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

n

o

s

e

l

l

*




e

.

s

e

l

f

:

M

e

r

c

h

a

n

t

C

l

o

s

e

S

h

o

p

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

p

i

c

k

_

u

p

"

 

)

 

t

h

e

n




w

h

i

l

e

 

(

 

e

.

s

e

l

f

:

C

h

e

c

k

G

r

o

u

n

d

(

)

 

)

 

d

o




>

*

G

o

r

n

o

l

i

n

 

p

i

c

k

s

 

a

n

 

i

t

e

m

 

u

p

 

f

r

o

m

 

t

h

e

 

g

r

o

u

n

d

 

a

n

d

 

s

a

y

s

,

 

'

H

e

y

!

 

L

o

o

k

 

w

h

a

t

 

I

 

f

o

u

n

d

!

 

A

n

o

t

h

e

r

 

p

i

e

c

e

 

o

f

 

r

u

b

b

i

s

h

 

f

o

r

 

m

y

 

t

r

a

i

l

e

r

.

.

.

 

M

u

s

t

 

b

e

 

m

y

 

l

u

c

k

y

 

d

a

y

.

*






















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

G

o

r

n

o

l

i

n

 

s

a

y

s

:

*

*

 

G

r

e

e

t

i

n

g

s

,

 

m

y

 

f

e

l

l

o

w

 

t

r

a

v

e

l

e

r

.

 

I

 

a

m

 

G

o

r

n

o

l

i

n

 

Z

o

t

,

 

t

r

a

v

e

l

i

n

g

 

m

e

r

c

h

a

n

t

 

o

f

 

f

i

n

e

 

w

a

r

e

s

.

 

P

l

e

a

s

e

.

 

T

a

k

e

 

a

 

l

o

o

k

 

a

t

 

w

h

a

t

 

I

 

h

a

v

e

 

t

o

 

o

f

f

e

r

.



















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

 

1

 

o

r

 

e

.

w

p

 

=

=

 

6

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

S

e

t

R

u

n

n

i

n

g

(

t

r

u

e

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

 

4

 

o

r

 

e

.

w

p

 

=

=

 

7

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

S

e

t

R

u

n

n

i

n

g

(

f

a

l

s

e

)

;





