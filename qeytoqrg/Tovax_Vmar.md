# Tovax Vmar

[Tovax Vmar](/npc/4020) is a level 10 Human Necromancer that spawns in [Qeynos Hills](/zone/4).

Their primary faction is [Bloodsabers](/faction/221).





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







i

f

 

*

*

F

a

c

t

i

o

n

*

*

 

>

=

 

A

p

p

r

e

h

e

n

s

i

v

e

 

t

h

e

n




>

*

*

T

o

v

a

x

 

V

m

a

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

?

 

 

W

h

o

 

t

h

e

 

h

e

c

k

 

a

r

e

 

y

o

u

 

a

n

d

 

h

o

w

 

d

o

 

y

o

u

 

k

n

o

w

 

m

y

 

n

a

m

e

?

!

 

 

N

e

v

e

r

 

m

i

n

d

.

.

.

 

 

J

u

s

t

 

l

e

a

v

e

 

m

e

 

a

l

o

n

e

!




e

l

s

e




*

*

T

o

v

a

x

 

V

m

a

r

 

s

a

y

s

 

o

n

e

 

o

f

 

t

h

e

 

f

o

l

l

o

w

i

n

g

:

*

*







>

I

 

d

i

d

n

'

t

 

k

n

o

w

 

S

l

i

m

e

 

c

o

u

l

d

 

s

p

e

a

k

 

c

o

m

m

o

n

.

 

G

o

 

b

a

c

k

 

t

o

 

t

h

e

 

s

e

w

e

r

 

b

e

f

o

r

e

 

I

 

l

o

s

e

 

m

y

 

t

e

m

p

e

r

.







>

I

s

 

t

h

a

t

 

y

o

u

r

 

B

R

E

A

T

H

,

 

o

r

 

d

i

d

 

s

o

m

e

t

h

i

n

g

 

d

i

e

 

i

n

 

h

e

r

e

?

 

N

o

w

 

g

o

 

a

w

a

y

!







>

I

 

w

o

n

d

e

r

 

h

o

w

 

m

u

c

h

 

I

 

c

o

u

l

d

 

g

e

t

 

f

o

r

 

t

h

e

 

t

o

n

g

u

e

 

o

f

 

a

 

b

l

i

t

h

e

r

i

n

g

 

f

o

o

l

?

 

L

e

a

v

e

 

b

e

f

o

r

e

 

I

 

d

e

c

i

d

e

 

t

o

 

f

i

n

d

 

o

u

t

 

f

o

r

 

m

y

s

e

l

f

.







>

O

h

 

l

o

o

k

,

 

a

 

t

a

l

k

i

n

g

 

l

u

m

p

 

o

f

 

r

e

f

u

s

e

.

 

 

H

o

w

 

n

o

v

e

l

!






















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

R

u

n

n

i

n

g

(

t

r

u

e

)

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

 

1

3

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

 

>

 

0

 

a

n

d

 

e

.

w

p

 

<

 

3

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

R

u

n

n

i

n

g

(

f

a

l

s

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

w

p

 

=

=

 

3

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

R

u

n

n

i

n

g

(

t

r

u

e

)

;




i

f

(

Z

o

n

e

T

i

m

e

 

>

 

1

8

 

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

4

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

W

a

y

p

o

i

n

t

s

(

)

;




e

.

s

e

l

f

:

A

s

s

i

g

n

W

a

y

p

o

i

n

t

s

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

2

1

,

2

5

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

R

u

n

n

i

n

g

(

f

a

l

s

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

Z

o

n

e

T

i

m

e

 

>

 

6

 

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

 

<

 

2

0

)

 

t

h

e

n




*

*

T

o

v

a

x

 

V

m

a

r

 

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

 

>

 

2

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

G

r

i

d

(

)

 

<

 

2

6

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

 

1

 

o

r

 

e

.

w

p

 

=

=

 

3

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

R

u

n

n

i

n

g

(

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

R

u

n

n

i

n

g

(

f

a

l

s

e

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

G

r

i

d

(

)

 

>

 

2

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

G

r

i

d

(

)

 

<

 

2

6

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

 

2

 

o

r

 

e

.

w

p

 

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

T

o

v

a

x

 

V

m

a

r

 

s

a

y

s

:

*

*

 

S

'

r

a

g

g

 

i

s

 

g

o

i

n

g

 

t

o

 

h

a

v

e

 

m

y

 

h

e

a

d

 

f

o

r

 

l

o

s

i

n

g

 

t

h

a

t

 

l

e

t

t

e

r

.

.

.




e

l

s

e

i

f

(

e

.

w

p

 

=

=

 

4

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

W

a

y

p

o

i

n

t

s

(

)

;




e

.

s

e

l

f

:

A

s

s

i

g

n

W

a

y

p

o

i

n

t

s

(

1

3

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

R

u

n

n

i

n

g

(

f

a

l

s

e

)

;






















#

#

 

D

e

p

a

r

t

 

f

r

o

m

 

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

 

>

 

2

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

G

r

i

d

(

)

 

<

 

2

6

 

a

n

d

 

e

.

w

p

 

=

=

 

1

)

 

t

h

e

n




*

*

S

p

a

w

n

s

 

o

n

 

g

r

o

u

n

d

:

*

*

 

 

<

i

m

g

 

s

t

y

l

e

=

"

b

a

c

k

g

r

o

u

n

d

:

u

r

l

(

/

s

t

a

t

i

c

/

i

c

o

n

s

/

b

l

a

n

k

_

s

l

o

t

.

g

i

f

)

;

w

i

d

t

h

:

2

0

p

x

;

h

e

i

g

h

t

:

2

0

p

x

;

"

 

s

r

c

=

"

/

s

t

a

t

i

c

/

i

c

o

n

s

/

i

t

e

m

_

8

6

6

.

p

n

g

"

 

a

l

t

=

"

"

 

/

>

 

<

a




 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

h

r

e

f

=

"

/

i

t

e

m

/

1

8

8

0

2

"

 

d

a

t

a

-

u

r

l

=

"

1

8

8

0

2

"

 

c

l

a

s

s

=

"

t

o

o

l

t

i

p

-

l

i

n

k

 

l

i

n

k

"

>

A

 

S

e

a

l

e

d

 

L

e

t

t

e

r

<

/

a

>

 

a

t

 

l

o

c

a

t

i

o

n

.





