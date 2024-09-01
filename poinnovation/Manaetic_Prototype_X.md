# Manaetic Prototype X

[Manaetic Prototype X](/npc/206053) is a level 66 Clockwork Brain Warrior that spawns in [Plane of Innovation](/zone/206).

Their primary faction is [KOS Plane of Innovation](/faction/5030).





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

e

l

e

p

o

r

t

"

 

)

 

t

h

e

n







e

q

.

s

e

t

_

t

i

m

e

r

(

"

t

e

l

e

p

o

r

t

"

,

 

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

2

,

 

3

0

)

 

*

 

1

0

0

0

)

;




l

o

c

a

l

 

t

a

r

g

e

t

 

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

T

a

r

g

e

t

(

)

;







i

f

 

(

 

t

a

r

g

e

t

 

a

n

d

 

t

a

r

g

e

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

H

a

t

e

(

t

a

r

g

e

t

,

 

1

)

;




i

f

 

(

 

t

a

r

g

e

t

:

I

s

C

l

i

e

n

t

(

)

 

)

 

t

h

e

n




t

a

r

g

e

t

:

C

a

s

t

T

o

C

l

i

e

n

t

(

)

:

M

o

v

e

P

C

(

2

0

6

,

 

1

,

 

-

4

7

3

,

 

2

,

 

1

2

8

*

2

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

b

o

u

n

d

s

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

G

e

t

X

(

)

 

>

 

-

1

0

0

 

o

r

 

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

X

(

)

 

<

 

-

4

0

0

 

)

 

t

h

e

n




>

*

M

a

n

a

e

t

i

c

 

P

r

o

t

o

t

y

p

e

 

X

 

r

a

t

t

l

e

s

 

v

i

o

l

e

n

t

l

y

 

a

n

d

 

d

i

s

a

p

p

e

a

r

s

!

*




e

.

s

e

l

f

:

G

M

M

o

v

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

a

s

t

T

o

N

P

C

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

P

o

i

n

t

X

(

)

,

 

e

.

s

e

l

f

:

C

a

s

t

T

o

N

P

C

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

P

o

i

n

t

Y

(

)

,

 

e

.

s

e

l

f

:

C

a

s

t

T

o

N

P

C

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

P

o

i

n

t

Z

(

)

,

 

e

.

s

e

l

f

:

C

a

s

t

T

o

N

P

C

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

P

o

i

n

t

H

(

)

)

;




*

*

M

a

n

a

e

t

i

c

 

P

r

o

t

o

t

y

p

e

 

X

 

c

a

s

t

s

:

*

*

 

[

B

a

l

a

n

c

e

 

o

f

 

t

h

e

 

N

a

m

e

l

e

s

s

]

(

/

s

p

e

l

l

/

3

2

3

0

)

 

o

n

 

t

h

e

m

s

e

l

v

e

s

.




*

*

M

a

n

a

e

t

i

c

 

P

r

o

t

o

t

y

p

e

 

X

*

*

 

c

l

e

a

r

s

 

h

a

t

e

 

l

i

s

t

.




e

.

s

e

l

f

:

H

e

a

l

(

)

;






















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

 

 

M

a

n

a

e

t

i

c

 

P

r

o

t

o

t

y

p

e

 

X

 

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

s

e

t

_

t

i

m

e

r

(

"

t

e

l

e

p

o

r

t

"

,

 

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

2

,

 

3

0

)

 

*

 

1

0

0

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

b

o

u

n

d

s

c

h

e

c

k

*

 

f

o

r

 

3

 

s

e

c

o

n

d

s




e

l

s

e




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

t

e

l

e

p

o

r

t

*




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

b

o

u

n

d

s

c

h

e

c

k

*





