# an elite gnoll guard

[an elite gnoll guard](/npc/17112) is a level 11 Gnoll Warrior that spawns in [Blackburrow](/zone/17).

Their primary faction is [Sabertooths of Blackburrow](/faction/306).





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




l

o

c

a

l

 

s

p

 

=

 

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

S

p

a

w

n

P

o

i

n

t

I

D

(

)

;




l

o

c

a

l

 

s

p

a

w

n

 

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

S

p

a

w

n

B

y

I

D

(

s

p

)

;




s

p

a

w

n

:

S

e

t

R

e

s

p

a

w

n

T

i

m

e

r

(

2

3

0

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

 

1

2

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

 

C

o

m

b

a

t




i

f

 

a

n

 

e

l

i

t

e

 

g

n

o

l

l

 

g

u

a

r

d

 

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

 

T

i

m

e

r

(

s

)




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

d

e

p

o

p

*




*

*

a

n

 

e

l

i

t

e

 

g

n

o

l

l

 

g

u

a

r

d

 

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










f

u

n

c

t

i

o

n

 

e

v

e

n

t

_

d

e

a

t

h

(

e

)




l

o

c

a

l

 

s

p

 

=

 

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

S

p

a

w

n

P

o

i

n

t

I

D

(

)

;




l

o

c

a

l

 

s

p

a

w

n

 

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

S

p

a

w

n

B

y

I

D

(

s

p

)

;




s

p

a

w

n

:

S

e

t

R

e

s

p

a

w

n

T

i

m

e

r

(

3

6

0

)

;


