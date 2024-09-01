# a minion of Maareq

[a minion of Maareq](/npc/207297) is a level 40 Mouth of Insanity Warrior that spawns in [Torment, the Plane of Pain](/zone/207).





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

c

h

e

c

k

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

4

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

a

 

m

i

n

i

o

n

 

o

f

 

M

a

a

r

e

q

 

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

c

h

e

c

k

"

 

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

)

 

<

 

1

0

 

)

 

t

h

e

n




*

*

S

i

g

n

a

l

e

d

 

t

o

:

*

*

 

 

[

M

a

a

r

e

q

 

t

h

e

 

P

r

o

p

h

e

t

]

(

/

n

p

c

/

2

0

7

0

0

4

)




>

*

a

 

m

i

n

i

o

n

 

o

f

 

M

a

a

r

e

q

 

a

d

h

e

r

e

s

 

t

o

 

M

a

a

r

e

q

'

s

 

f

l

e

s

h

 

a

n

d

 

i

s

 

q

u

i

c

k

l

y

 

a

b

s

o

r

b

e

d

!

*




*

*

a

 

m

i

n

i

o

n

 

o

f

 

M

a

a

r

e

q

 

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

m

o

v

e

"

 

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





