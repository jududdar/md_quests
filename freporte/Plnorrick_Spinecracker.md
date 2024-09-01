# Plnorrick Spinecracker

[Plnorrick Spinecracker](/npc/10163) is a level 30 Troll Warrior that spawns in [East Freeport](/zone/10).

Their primary faction is [Steel Warriors](/faction/311).





#

#

 

D

i

a

l

o

g




*

*

Y

o

u

 

s

a

y

:

*

*

 

`

h

a

i

l

`







>

*

*

P

l

n

o

r

r

i

c

k

 

S

p

i

n

e

c

r

a

c

k

e

r

 

s

a

y

s

:

*

*

 

W

h

a

t

 

d

o

 

y

o

u

 

w

a

n

t

?

 

I

 

d

o

n

'

t

 

h

a

v

e

 

a

n

y

 

s

p

a

r

e

 

c

h

a

n

g

e

.



















#

#

 

S

i

g

n

a

l

s




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




r

e

t

u

r

n

;










l

o

c

a

l

 

t

u

r

n

,

 

b

a

r

d

;







i

f

 

(

 

e

.

s

i

g

n

a

l

 

=

=

 

1

 

)

 

t

h

e

n




>

*

*

P

l

n

o

r

r

i

c

k

 

S

p

i

n

e

c

r

a

c

k

e

r

 

s

a

y

s

:

*

*

 

Y

e

s

.

 

W

e

 

s

h

a

l

l

 

l

i

v

e

 

t

o

g

e

t

h

e

r

.

 

W

e

 

s

h

a

l

l

 

b

e

 

s

t

r

o

n

g

.




t

u

r

n

 

=

 

t

r

u

e

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

s

i

g

n

a

l

 

=

=

 

2

 

)

 

t

h

e

n




>

*

*

P

l

n

o

r

r

i

c

k

 

S

p

i

n

e

c

r

a

c

k

e

r

 

s

a

y

s

:

*

*

 

H

a

!

!

 

D

u

m

b

 

o

g

r

e

s

.

 

P

l

n

o

r

r

i

c

k

 

c

a

n

 

b

a

s

h

 

a

n

y

 

o

f

 

t

h

e

m

.




t

u

r

n

 

=

 

t

r

u

e

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

s

i

g

n

a

l

 

=

=

 

3

 

)

 

t

h

e

n




>

*

*

P

l

n

o

r

r

i

c

k

 

S

p

i

n

e

c

r

a

c

k

e

r

 

s

a

y

s

:

*

*

 

<

C

l

a

p

>

.

.

 

<

C

l

a

p

>

.

.

 

<

G

l

u

g

,

 

g

l

u

g

>

.

.

 

A

h

h

.

 

I

 

l

o

v

e

 

t

h

a

t

 

s

o

n

g

.

 

<

H

i

c

!

!

>




t

u

r

n

 

=

 

t

r

u

e

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

s

i

g

n

a

l

 

=

=

 

5

 

)

 

t

h

e

n




>

*

*

P

l

n

o

r

r

i

c

k

 

S

p

i

n

e

c

r

a

c

k

e

r

 

s

a

y

s

:

*

*

 

S

m

a

s

h

 

E

r

u

d

i

n

!

!

 

T

h

e

y

 

a

r

e

 

w

e

a

k

.

 

T

h

e

y

 

s

h

o

u

l

d

 

b

e

 

d

e

s

t

r

o

y

e

d

!

!




t

u

r

n

 

=

 

t

r

u

e

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

s

i

g

n

a

l

 

=

=

 

1

0

 

)

 

t

h

e

n
















>

*

*

P

l

n

o

r

r

i

c

k

 

S

p

i

n

e

c

r

a

c

k

e

r

 

s

a

y

s

:

*

*

 

M

y

 

f

i

s

t

 

w

i

l

l

 

u

n

i

t

e

 

w

i

t

h

 

y

o

u

r

 

f

a

c

e

.




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

1

0

0

1

2

)

,

5

0

0

)

;

 




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

I

m

x

i

l

 

T

b

r

o

w

]

(

/

n

p

c

/

1

0

0

1

2

)










i

f

 

(

 

t

u

r

n

 

)

 

t

h

e

n




b

a

r

d

 

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

1

0

1

4

1

)

;

	

	

	




i

f

 

(

 

n

o

t

 

b

a

r

d

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




b

a

r

d

 

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

1

0

1

5

8

)

;

	

	







i

f

 

(

 

n

o

t

 

b

a

r

d

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




b

a

r

d

 

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

1

0

1

6

5

)

;

	

	







i

f

 

(

 

b

a

r

d

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

F

a

c

e

T

a

r

g

e

t

(

b

a

r

d

)

;








