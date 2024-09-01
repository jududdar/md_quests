# Bizzznawa

[Bizzznawa](/npc/126220) is a level 41 Bixie Warrior that spawns in [Plane of Mischief](/zone/126).

Their primary faction is [Denizens of Mischief](/faction/437).





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

f

o

l

l

o

w

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

f

o

l

l

o

w

"

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

o

b

t

y

p

e

I

D

 

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

1

2

6

2

3

5

)

;







i

f

(

m

o

b

t

y

p

e

I

D

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

 

f

o

l

l

o

w

_

m

o

b

 

=

 

m

o

b

t

y

p

e

I

D

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

f

o

l

l

o

w

(

f

o

l

l

o

w

_

m

o

b

,

0

)

;




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

f

o

l

l

o

w

*








