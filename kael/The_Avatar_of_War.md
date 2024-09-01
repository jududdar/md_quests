# The Avatar of War

[The Avatar of War](/npc/113244) is a level 70 Rallos Zek Warrior that spawns in [Kael Drakkel](/zone/113).

Their primary faction is [KOS_Kael](/faction/5049).





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

T

h

e

 

A

v

a

t

a

r

 

o

f

 

W

a

r

 

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

 

C

o

m

b

a

t




i

f

 

T

h

e

 

A

v

a

t

a

r

 

o

f

 

W

a

r

 

e

n

t

e

r

s

 

c

o

m

b

a

t

 

 

t

h

e

n




i

f

(

n

o

t

 

e

q

.

i

s

_

p

a

u

s

e

d

_

t

i

m

e

r

(

"

d

e

p

o

p

"

)

)

 

t

h

e

n




e

q

.

p

a

u

s

e

_

t

i

m

e

r

(

"

d

e

p

o

p

"

)

;







e

l

s

e




e

q

.

r

e

s

u

m

e

_

t

i

m

e

r

(

"

d

e

p

o

p

"

)

;



















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

A

v

a

t

a

r

"

)

;


