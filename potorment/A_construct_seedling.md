# A construct seedling

[A construct seedling](/npc/207295) is a level 56 Mouth of Insanity Warrior that spawns in [Torment, the Plane of Pain](/zone/207).

Their primary faction is [Servants of Saryrn](/faction/1624).





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

 

1

0

0

 

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

m

o

v

e

*

 

f

o

r

 

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

m

o

v

e

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

m

o

v

e

*

 

f

o

r

 

6

 

s

e

c

o

n

d

s







l

o

c

a

l

 

b

o

s

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

2

0

7

0

0

3

)

;

 




i

f

 

(

 

n

o

t

 

b

o

s

s

 

o

r

 

n

o

t

 

b

o

s

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




*

*

A

 

c

o

n

s

t

r

u

c

t

 

s

e

e

d

l

i

n

g

 

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

b

o

s

s

:

G

e

t

X

(

)

,

 

b

o

s

s

:

G

e

t

Y

(

)

,

 

b

o

s

s

:

G

e

t

Z

(

)

 

-

 

5

.

5

,

 

-

1

,

 

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

A

 

c

o

n

s

t

r

u

c

t

 

s

e

e

d

l

i

n

g

 

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

 

 

A

 

c

o

n

s

t

r

u

c

t

 

s

e

e

d

l

i

n

g

 

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





