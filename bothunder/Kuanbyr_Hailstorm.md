# Kuanbyr Hailstorm

[Kuanbyr Hailstorm](/npc/209061) is a level 67 Giant Warrior that spawns in [Bastion of Thunder](/zone/209).

Their primary faction is [Greater Jord Giants](/faction/1610).l

o

c

a

l

 

T

Y

P

E

S

 

=

 

{

 

2

0

9

0

5

8

,

 

2

0

9

0

5

7

,

 

2

0

9

0

5

6

 

}

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

 

 

K

u

a

n

b

y

r

 

H

a

i

l

s

t

o

r

m

 

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

t

i

c

k

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

i

c

k

*



















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

i

c

k

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

 

n

p

c

;







f

o

r

 

_

,

 

i

d

 

i

n

 

i

p

a

i

r

s

(

T

Y

P

E

S

)

 

d

o







n

p

c

 

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

N

P

C

B

y

N

P

C

T

y

p

e

I

D

(

i

d

)

;







i

f

 

(

 

n

p

c

 

a

n

d

 

n

p

c

.

v

a

l

i

d

 

a

n

d

 

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

 

a

n

d

 

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




n

p

c

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

,

 

1

)

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

Y

(

)

 

>

 

-

1

8

0

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








