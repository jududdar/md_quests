# Undogo Digolo

[Undogo Digolo](/npc/127015) is a level 65 Totem Ranger that spawns in [Plane of Growth](/zone/127).

Their primary faction is [Servants of Tunare](/faction/438).





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

 

 

U

n

d

o

g

o

 

D

i

g

o

l

o

 

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




H

e

l

p

M

e

(

e

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

h

e

l

p

*

 

f

o

r

 

3

0

0

 

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

h

e

l

p

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

h

e

l

p

"

 

)

 

t

h

e

n




*

*

U

n

d

o

g

o

 

D

i

g

o

l

o

 

s

h

o

u

t

s

:

*

*

 

<

s

p

a

n

 

c

l

a

s

s

=

"

t

e

x

t

-

d

a

n

g

e

r

"

>

U

n

d

o

g

o

,

 

o

l

d

o

g

o

,

 

g

a

b

a

,

 

d

a

g

a

!

<

/

s

p

a

n

>




H

e

l

p

M

e

(

e

)

;













f

u

n

c

t

i

o

n

 

H

e

l

p

M

e

(

e

)







l

o

c

a

l

 

h

e

l

p

e

r

s

 

=

 

{




[

1

2

7

0

2

7

]

 

=

 

1

,

	




[

1

2

7

1

0

3

]

 

=

 

1

,

	




[

1

2

7

0

2

6

]

 

=

 

1

,

	




}

;







l

o

c

a

l

 

l

i

s

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

N

P

C

L

i

s

t

(

)

;







i

f

 

(

 

l

i

s

t

 

)

 

t

h

e

n







f

o

r

 

n

p

c

 

i

n

 

l

i

s

t

.

e

n

t

r

i

e

s

 

d

o







i

f

 

(

 

h

e

l

p

e

r

s

[

n

p

c

:

G

e

t

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

)

]

 

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

 

)

 

t

h

e

n




n

p

c

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

M

o

v

e

T

o

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

,

 

f

a

l

s

e

)

;











