# a putrid skeleton

[a putrid skeleton](/npc/4148) is a level 5 Skeleton Warrior that spawns in [Qeynos Hills](/zone/4).

Their primary faction is [Skeleton](/faction/110).l

o

c

a

l

 

d

e

s

p

a

w

n

t

i

m

e

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

 

=

=

 

3

6

5

1

0

5

 

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

 

=

=

 

3

6

5

1

0

6

)

 

t

h

e

n




d

e

s

p

a

w

n

t

i

m

e

 

=

 

0

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

 

8

6

4

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




d

e

s

p

a

w

n

t

i

m

e

 

=

 

1

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

 

Z

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

 

2

6

 

a

n

d

 

d

e

s

p

a

w

n

t

i

m

e

 

=

=

 

1

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

w

p

 

=

=

 

0

 

a

n

d

 

Z

o

n

e

T

i

m

e

 

>

 

7

 

a

n

d

 

Z

o

n

e

T

i

m

e

 

<

 

2

0

)

 

t

h

e

n




d

e

s

p

a

w

n

t

i

m

e

 

=

 

0

;




*

*

a

 

p

u

t

r

i

d

 

s

k

e

l

e

t

o

n

 

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








