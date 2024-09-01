# Scruffy

[Scruffy](/npc/4155) is a level 1 Rat Warrior that spawns in [Qeynos Hills](/zone/4).

Their primary faction is [Giant Rat](/faction/86).





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

e

.

s

e

l

f

:

G

e

t

G

r

i

d

(

)

 

=

=

 

1

3

 

a

n

d

 

e

.

w

p

 

>

 

0

 

a

n

d

 

e

.

w

p

 

<

 

3

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




e

l

s

e

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

G

e

t

G

r

i

d

(

)

 

=

=

 

1

3

 

a

n

d

 

e

.

w

p

 

=

=

 

3

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

 

m

a

t

h

.

r

a

n

d

o

m

(

1

,

1

0

0

)

 

<

 

2

0

)

 

t

h

e

n




*

*

S

c

r

u

f

f

y

 

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








