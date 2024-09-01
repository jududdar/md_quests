# Maareq the Prophet

[Maareq the Prophet](/npc/207004) is a level 70 Human Warrior that spawns in [Torment, the Plane of Pain](/zone/207).

Their primary faction is [Servants of Saryrn](/faction/1624).l

o

c

a

l

 

p

o

w

e

r

 

=

 

0

;




l

o

c

a

l

 

s

t

a

t

e

 

=

 

0

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




p

o

w

e

r

 

=

 

0

;




s

t

a

t

e

 

=

 

0

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

m

i

n

i

o

n

*

 

f

o

r

 

5

 

s

e

c

o

n

d

s




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

r

e

v

e

r

t

*




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

m

i

n

i

o

n

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

u

p

g

r

a

d

e

*




i

f

 

(

 

s

t

a

t

e

 

>

 

0

 

)

 

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

r

e

v

e

r

t

*

 

f

o

r

 

4

8

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

m

i

n

i

o

n

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

 

m

o

b

 

=

 

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

2

9

7

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

 

0

,

 

*

*

x

:

*

*

 

-

2

5

)




m

o

b

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

 

t

r

u

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

Z

(

)

 

<

 

4

4

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

Z

(

)

 

>

 

4

7

5

 

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




*

*

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







]

]







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

u

p

g

r

a

d

e

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

t

o

p

_

t

i

m

e

r

(

e

.

t

i

m

e

r

)

;







i

f

 

(

 

s

t

a

t

e

 

=

=

 

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

 

r

a

i

s

e

s

 

h

i

s

 

a

r

m

s

 

t

o

w

a

r

d

s

 

t

h

e

 

s

k

y

 

a

n

d

 

s

c

r

e

a

m

s

!

 

H

i

s

 

e

x

p

o

s

e

d

 

s

k

i

n

 

b

u

l

g

e

s

 

a

n

d

 

w

r

i

t

h

e

s

,

 

a

s

 

t

h

e

 

c

r

e

a

t

u

r

e

s

 

t

h

a

t

 

c

l

u

n

g

 

t

o

 

h

i

m

 

m

o

v

e

 

b

e

n

e

a

t

h

 

i

t

s

 

s

u

r

f

a

c

e

.

*




>

*

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

 

s

h

o

u

t

s

 

'

M

y

 

p

r

o

p

h

e

c

y

 

w

a

s

 

f

u

l

f

i

l

l

e

d

 

f

o

r

 

S

a

r

y

r

n

.

 

 

Y

o

u

r

 

f

a

t

e

 

s

h

a

l

l

 

c

o

m

e

 

t

o

 

f

r

u

i

t

i

o

n

 

a

s

 

w

e

l

l

!

 

 

I

 

h

a

v

e

 

a

 

s

p

e

c

i

a

l

 

v

i

s

i

o

n

 

f

o

r

 

y

o

u

.

 

 

N

o

w

,

 

s

t

e

p

 

f

o

r

w

a

r

d

 

l

i

k

e

 

t

h

e

 

o

b

e

d

i

e

n

t

 

c

a

t

t

l

e

 

y

o

u

 

a

r

e

.

 

 

L

e

t

 

u

s

 

b

e

g

i

n

 

t

h

i

s

 

h

a

r

v

e

s

t

 

o

f

 

p

a

i

n

!

'

*







e

.

s

e

l

f

:

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

s

p

e

c

i

a

l

_

a

b

i

l

i

t

i

e

s

"

,

 

"

5

,

1

,

2

5

"

)

;

 




e

.

s

e

l

f

:

C

h

a

n

g

e

S

i

z

e

(

1

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

 

s

t

a

t

e

 

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

 

s

a

y

s

:

*

*

 

Y

o

u

r

 

a

s

s

a

u

l

t

 

o

n

l

y

 

p

r

o

l

o

n

g

s

 

t

h

e

 

i

n

e

v

i

t

a

b

l

e

!

 

 

I

 

c

a

n

 

f

e

e

l

 

t

h

e

 

f

e

a

r

 

d

r

i

p

p

i

n

g

 

f

o

r

 

y

o

u

.

 

 

G

i

v

e

 

i

n

t

o

 

i

t

.

 

 

G

i

v

e

 

u

p

 

w

h

i

l

e

 

y

o

u

 

s

t

i

l

l

 

h

a

v

e

 

e

n

o

u

g

h

 

e

n

e

r

g

y

 

t

o

 

s

u

f

f

e

r

 

p

r

o

p

e

r

l

y

!




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

M

e

s

s

a

g

e

C

l

o

s

e

(

e

.

s

e

l

f

,

 

t

r

u

e

,

 

2

0

0

,

 

0

,

 

"

A

 

h

o

r

r

i

f

i

c

 

r

o

a

r

 

r

e

v

e

r

b

e

r

a

t

e

s

 

t

h

r

o

u

g

h

o

u

t

 

t

h

e

 

z

o

n

e

!

 

 

E

v

e

r

y

 

s

u

r

f

a

c

e

 

s

h

a

k

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

 

f

o

r

 

a

 

m

o

m

e

n

t

 

a

s

 

t

h

e

 

s

o

u

n

d

 

r

o

l

l

s

 

p

a

s

t

 

y

o

u

!

"

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

T

e

x

t

u

r

e

(

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

S

e

t

R

a

c

e

(

2

8

1

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

G

e

n

d

e

r

(

2

)

;




e

.

s

e

l

f

:

C

h

a

n

g

e

S

i

z

e

(

1

2

)

;




e

.

s

e

l

f

:

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

s

p

e

c

i

a

l

_

a

b

i

l

i

t

i

e

s

"

,

 

"

5

,

0

,

0

"

)

;

 




e

.

s

e

l

f

:

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

s

p

e

c

i

a

l

_

a

b

i

l

i

t

i

e

s

"

,

 

"

4

,

1

,

1

0

"

)

;

 







e

l

s

e

i

f

 

(

 

s

t

a

t

e

 

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

 

r

a

d

i

a

t

e

s

 

w

i

t

h

 

r

a

g

e

!

 

 

T

h

e

 

f

e

r

o

c

i

t

y

 

o

f

 

i

t

'

s

 

a

t

t

a

c

k

s

 

i

n

c

r

e

a

s

e

s

 

d

r

a

m

a

t

i

c

a

l

l

y

 

a

s

 

i

t

'

s

 

s

k

i

n

 

b

e

g

i

n

s

 

t

o

 

b

u

b

b

l

e

 

a

n

d

 

b

u

r

s

t

 

i

n

 

p

l

a

c

e

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

C

h

a

n

g

e

S

i

z

e

(

1

7

)

;




e

.

s

e

l

f

:

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

a

t

t

a

c

k

_

d

e

l

a

y

"

,

 

"

8

"

)

;







s

t

a

t

e

 

=

 

s

t

a

t

e

 

+

 

1

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

r

e

v

e

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

t

o

p

_

t

i

m

e

r

(

e

.

t

i

m

e

r

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

T

e

x

t

u

r

e

(

1

6

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

a

c

e

(

1

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

G

e

n

d

e

r

(

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

C

h

a

n

g

e

S

i

z

e

(

7

)

;




e

.

s

e

l

f

:

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

s

p

e

c

i

a

l

_

a

b

i

l

i

t

i

e

s

"

,

 

"

5

,

0

,

0

"

)

;

 




e

.

s

e

l

f

:

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

s

p

e

c

i

a

l

_

a

b

i

l

i

t

i

e

s

"

,

 

"

4

,

0

,

0

"

)

;

 




e

.

s

e

l

f

:

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

a

t

t

a

c

k

_

d

e

l

a

y

"

,

 

"

1

2

"

)

;




p

o

w

e

r

 

=

 

0

;




s

t

a

t

e

 

=

 

0

;



















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




p

o

w

e

r

 

=

 

p

o

w

e

r

 

+

 

1

;







i

f

 

(

 

(

s

t

a

t

e

 

<

 

3

 

a

n

d

 

p

o

w

e

r

 

>

=

 

4

0

)

 

o

r

 

(

s

t

a

t

e

 

<

 

2

 

a

n

d

 

p

o

w

e

r

 

>

=

2

0

)

 

o

r

 

(

s

t

a

t

e

 

=

=

 

0

 

a

n

d

 

p

o

w

e

r

 

>

=

 

1

0

)

 

)

 

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

u

p

g

r

a

d

e

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

 

a

l

l

 

i

n

s

t

a

n

c

e

s

 

o

f

:

*

*

 

 

[

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

2

9

7

)







l

o

c

a

l

 

t

y

l

i

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

1

4

)

;

 




i

f

 

(

 

t

y

l

i

s

 

a

n

d

 

t

y

l

i

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




t

y

l

i

s

:

S

e

t

B

o

d

y

T

y

p

e

(

1

,

 

f

a

l

s

e

)

;

	





