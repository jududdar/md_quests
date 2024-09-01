# A Mystical Arbitor of Earth

[A Mystical Arbitor of Earth](/npc/218375) is a level 74 Earth Elemental Warrior that spawns in [Plane of Earth](/zone/218).

Their primary faction is [KOS](/faction/5017).l

o

c

a

l

 

P

L

A

N

A

R

_

P

R

O

J

E

C

T

I

O

N

_

T

Y

P

E

 

=

 

2

1

8

3

9

8

;













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

0

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

 

C

o

m

b

a

t




i

f

 

 

A

 

M

y

s

t

i

c

a

l

 

A

r

b

i

t

o

r

 

o

f

 

E

a

r

t

h

 

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

r

o

p

h

a

t

e

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

d

r

o

p

h

a

t

e

*



















l

o

c

a

l

 

r

a

t

i

o

 

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

H

P

R

a

t

i

o

(

)

;




i

f

 

(

 

r

a

t

i

o

 

<

 

5

0

 

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

 

>

 

r

a

t

i

o

 

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

G

e

t

G

u

a

r

d

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

G

e

t

G

u

a

r

d

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

G

e

t

G

u

a

r

d

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

P

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

H

P

(

)

 

+

 

m

a

t

h

.

f

l

o

o

r

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

M

a

x

H

P

(

)

 

*

 

0

.

3

)

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

r

o

p

h

a

t

e

"

)

 

t

h

e

n







i

f

 

(

 

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

)

 

<

 

0

.

0

5

 

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

R

e

m

o

v

e

F

r

o

m

H

a

t

e

L

i

s

t

(

t

a

r

g

e

t

)

;







e

q

.

d

e

b

u

g

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

N

a

m

e

(

)

.

.

"

 

d

r

o

p

p

e

d

 

t

a

r

g

e

t

 

f

r

o

m

 

h

a

t

e

 

l

i

s

t

 

(

"

.

.

t

a

r

g

e

t

:

G

e

t

N

a

m

e

(

)

.

.

"

)

"

,

 

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




e

q

.

d

e

b

u

g

(

"

A

r

b

i

t

o

r

 

d

e

p

o

p

"

)

;




*

*

A

 

M

y

s

t

i

c

a

l

 

A

r

b

i

t

o

r

 

o

f

 

E

a

r

t

h

 

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

s

p

a

w

n

2

(

P

L

A

N

A

R

_

P

R

O

J

E

C

T

I

O

N

_

T

Y

P

E

,

 

0

,

 

0

,

 

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

,

 

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

G

e

t

Z

(

)

,

 

0

)

;




e

q

.

s

i

g

n

a

l

(

P

L

A

N

A

R

_

P

R

O

J

E

C

T

I

O

N

_

T

Y

P

E

,

 

e

.

k

i

l

l

e

r

:

G

e

t

I

D

(

)

)

;

 


