# A storm watcher

[A storm watcher](/npc/209113) is a level 63 Nightmare Gargoyle Warrior that spawns in [Bastion of Thunder](/zone/209).





#

#

 

S

i

g

n

a

l

s




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

 

a

n

d

 

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




i

f

 

(

 

e

.

s

e

l

f

:

C

a

l

c

u

l

a

t

e

D

i

s

t

a

n

c

e

(

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

X

(

)

,

 

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

Y

(

)

,

 

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

Z

(

)

)

 

<

 

1

5

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

A

d

d

T

o

H

a

t

e

L

i

s

t

(

c

l

i

e

n

t

,

 

1

)

;








