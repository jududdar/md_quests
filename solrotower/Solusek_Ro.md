# Solusek Ro

[Solusek Ro](/npc/212025) is a level 80 Solusek Ro Warrior that spawns in [Tower of Solusek Ro](/zone/212).

Their primary faction is [KOS](/faction/5017).





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

 

 

S

o

l

u

s

e

k

 

R

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

a

n

t

i

_

c

h

e

a

t

*

 

f

o

r

 

3

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

a

n

t

i

_

c

h

e

a

t

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

a

n

t

i

_

c

h

e

a

t

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

Z

(

)

 

<

 

2

4

0

 

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

H

P

R

a

t

i

o

(

)

 

<

 

5

0

 

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

L

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




f

o

r

 

n

p

c

 

i

n

 

n

p

c

L

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

 

=

=

 

2

1

2

0

4

1

 

a

n

d

 

n

o

t

 

n

p

c

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

 




n

p

c

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

D

a

m

a

g

e

(

1

0

0

0

0

0

)

;






















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

S

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

A

 

P

l

a

n

a

r

 

P

r

o

j

e

c

t

i

o

n

]

(

/

n

p

c

/

2

1

2

4

2

0

)

 

a

t

 

(

*

*

y

:

*

*

 

-

8

1

5

,

 

*

*

x

:

*

*

 

0

)




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

A

 

P

l

a

n

a

r

 

P

r

o

j

e

c

t

i

o

n

]

(

/

n

p

c

/

2

1

2

4

2

0

)


