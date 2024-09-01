# Bartender

[Bartender](/npc/5069) is a level 45 Human Shopkeeper that spawns in [Highpass Hold](/zone/5).

Their primary faction is [Merchants of Highpass](/faction/331).





#

#

 

S

i

g

n

a

l

s




i

f

(

e

.

s

i

g

n

a

l

 

=

=

 

1

)

 

t

h

e

n




>

*

*

B

a

r

t

e

n

d

e

r

 

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

 

b

o

s

s

 

m

i

g

h

t

 

n

e

e

d

 

s

o

m

e

 

h

e

l

p

!




l

o

c

a

l

 

s

t

a

n

o

s

 

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

M

o

b

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

5

0

8

8

)

;

 




i

f

 

(

 

s

t

a

n

o

s

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




e

.

s

e

l

f

:

M

o

v

e

T

o

(

s

t

a

n

o

s

:

G

e

t

X

(

)

,

 

s

t

a

n

o

s

:

G

e

t

Y

(

)

,

 

s

t

a

n

o

s

:

G

e

t

Z

(

)

,

 

-

1

,

 

f

a

l

s

e

)

;








