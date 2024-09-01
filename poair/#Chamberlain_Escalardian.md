# Chamberlain Escalardian

[Chamberlain Escalardian](/npc/215411) is a level 70 Animated Armor Warrior that spawns in [Plane of Air](/zone/215).

Their primary faction is [KOS](/faction/5017).





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




*

*

D

e

s

p

a

w

n

 

N

P

C

:

*

*

 

 

[

a

r

m

o

r

 

g

u

y

]

(

/

n

p

c

/

2

1

5

4

1

8

)
















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

 

 

C

h

a

m

b

e

r

l

a

i

n

 

E

s

c

a

l

a

r

d

i

a

n

 

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

1

6

6

6

 

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








