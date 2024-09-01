# Jaled Dar`s shade

[Jaled Dar`s shade](/npc/123011) is a level 70 Dragon Cleric that spawns in [Dragon Necropolis](/zone/123).

Their primary faction is [Jaled Dar](/faction/433).l

o

c

a

l

 

S

H

O

U

T

S

 

=

 

{




"

T

r

a

k

a

n

o

n

,

 

m

y

 

f

r

i

e

n

d

,

 

y

o

u

 

B

E

T

R

A

Y

E

D

 

m

e

!

"

,




"

H

a

r

l

a

!

 

 

P

h

a

r

a

!

 

 

I

t

 

i

s

 

c

o

l

d

 

h

e

r

e

,

 

a

n

d

 

d

a

r

k

,

 

s

o

 

v

e

r

y

 

d

a

r

k

.

"

,




"

S

o

m

e

b

o

d

y

 

i

s

 

t

h

e

r

e

,

 

I

 

c

a

n

 

t

e

l

l

!

 

 

L

i

s

t

e

n

 

t

o

 

m

e

!

 

 

W

e

 

w

e

r

e

 

W

R

O

N

G

,

 

h

e

 

m

u

s

t

 

b

e

 

a

w

a

k

e

n

e

d

!

"

,




"

Z

l

a

n

d

i

c

a

r

,

 

I

 

k

n

o

w

 

y

o

u

 

a

r

e

 

h

e

r

e

,

 

y

o

u

 

a

r

e

 

a

l

w

a

y

s

 

h

e

r

e

!

 

 

D

o

 

n

o

t

 

i

g

n

o

r

e

 

m

e

,

 

y

o

u

 

m

u

s

t

 

l

i

s

t

e

n

.

.

.

.

w

e

 

m

u

s

t

 

t

a

l

k

.

"

,




"

R

e

l

e

a

s

e

 

h

i

m

.

.

.

.

.

.

.

.

.

.

.

.

.

.

r

e

l

e

a

s

e

 

h

i

m

.

.

.

.

.

r

e

l

e

a

s

e

.

.

.

M

E

!

"

,




}

;




l

o

c

a

l

 

n

e

x

t

S

h

o

u

t

 

=

 

1

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

z

o

n

e

s

h

o

u

t

*

 

f

o

r

 

2

4

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

d

e

p

o

p

"

,

 

4

8

 

*

 

6

0

 

*

 

6

0

 

*

 

1

0

0

0

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

z

o

n

e

s

h

o

u

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

 

n

o

t

 

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

 

a

n

d

 

S

H

O

U

T

S

[

n

e

x

t

S

h

o

u

t

]

 

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

h

o

u

t

(

S

H

O

U

T

S

[

n

e

x

t

S

h

o

u

t

]

)

;










n

e

x

t

S

h

o

u

t

 

=

 

n

e

x

t

S

h

o

u

t

 

+

 

1

;




i

f

 

(

 

n

o

t

 

S

H

O

U

T

S

[

n

e

x

t

S

h

o

u

t

]

 

)

 

t

h

e

n




n

e

x

t

S

h

o

u

t

 

=

 

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

J

a

l

e

d

 

D

a

r

-

s

 

s

h

a

d

e

 

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

J

a

l

e

d

 

D

a

r

-

s

 

s

h

a

d

e

 

s

a

y

s

:

*

*

 

M

o

r

t

a

l

!

 

Y

o

u

 

M

U

S

T

 

a

i

d

 

m

e

!

 

I

 

w

i

l

l

 

h

a

v

e

 

m

y

 

r

e

v

e

n

g

e

,

 

a

n

d

 

m

y

 

r

e

s

t

!




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

a

i

d

 

y

o

u

`







>

*

*

J

a

l

e

d

 

D

a

r

-

s

 

s

h

a

d

e

 

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

 

m

u

s

t

 

w

a

k

e

 

T

h

e

 

S

l

e

e

p

e

r

.

 

H

e

 

i

s

 

o

u

r

 

s

a

l

v

a

t

i

o

n

,

 

h

e

 

w

i

l

l

 

r

e

s

t

o

r

e

 

a

 

n

e

w

 

g

o

l

d

e

n

 

a

g

e

 

t

o

 

N

o

r

r

a

t

h

.

 

I

t

 

w

a

s

 

a

 

t

e

r

r

i

b

l

e

 

m

i

s

t

a

k

e

 

t

o

 

s

u

b

d

u

e

 

h

i

m

,

 

j

e

a

l

o

u

s

y

 

a

n

d

 

e

n

v

y

 

l

e

d

 

u

s

 

t

o

 

d

o

 

i

t

.

 

I

 

s

e

e

 

a

l

l

 

o

f

 

t

h

i

s

 

c

l

e

a

r

l

y

 

n

o

w

.




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

s

l

e

e

p

e

r

`







>

*

*

J

a

l

e

d

 

D

a

r

-

s

 

s

h

a

d

e

 

s

a

y

s

:

*

*

 

K

e

r

a

f

y

r

m

,

 

t

h

e

 

b

e

s

t

 

o

f

 

u

s

,

 

w

h

a

t

 

w

e

 

s

h

o

u

l

d

 

b

e

.

 

W

e

 

i

m

p

r

i

s

o

n

e

d

 

h

i

m

 

i

n

 

a

 

t

i

m

e

l

e

s

s

 

s

l

u

m

b

e

r

 

a

e

o

n

s

 

a

g

o

.

 

I

 

k

n

o

w

 

h

o

w

 

t

o

 

r

e

l

e

a

s

e

 

h

i

m

,

 

b

u

t

 

I

 

a

m

 

n

o

 

l

o

n

g

e

r

 

o

f

 

t

h

e

 

f

l

e

s

h

,

 

s

o

 

I

 

c

a

n

n

o

t

 

d

o

 

i

t

 

m

y

s

e

l

f

.

 

B

u

t

 

y

o

u

 

c

a

n

 

a

c

c

o

m

p

l

i

s

h

 

t

h

i

s

 

t

a

s

k

!




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

t

a

s

k

`







>

*

*

J

a

l

e

d

 

D

a

r

-

s

 

s

h

a

d

e

 

s

a

y

s

:

*

*

 

W

h

e

n

 

t

h

e

 

t

o

m

b

 

w

a

s

 

c

l

o

s

e

d

 

a

n

d

 

t

h

e

 

e

n

t

r

y

 

s

e

a

l

e

d

,

 

m

a

n

y

 

d

r

a

g

o

n

s

 

p

a

r

t

i

c

i

p

a

t

e

d

 

i

n

 

t

h

e

 

c

e

r

e

m

o

n

y

.

 

T

h

e

y

 

i

n

v

e

s

t

e

d

 

p

o

r

t

i

o

n

s

 

o

f

 

t

h

e

i

r

 

e

s

s

e

n

c

e

 

i

n

t

o

 

t

h

e

 

s

e

a

l

.

 

T

h

e

 

s

e

a

l

 

i

s

 

p

a

r

t

 

o

f

 

t

h

e

m

 

n

o

w

.

 

W

i

t

h

 

t

h

e

 

r

i

g

h

t

 

t

a

l

i

s

m

a

n

s

,

 

I

 

c

a

n

 

s

h

o

w

 

y

o

u

 

h

o

w

 

t

o

 

m

a

k

e

 

a

 

k

e

y

 

t

h

a

t

 

w

i

l

l

 

a

l

l

o

w

 

o

n

e

 

t

o

 

p

a

s

s

,

 

a

s

 

i

f

 

t

h

e

y

 

w

e

r

e

 

o

f

 

t

h

e

 

F

i

r

s

t

 

B

r

o

o

d

.

 

I

f

 

y

o

u

 

d

o

 

n

o

t

 

w

i

s

h

 

t

o

 

d

o

 

t

h

i

s

 

f

o

r

 

t

h

e

 

g

o

o

d

 

o

f

 

a

l

l

,

 

p

e

r

h

a

p

s

 

y

o

u

 

w

i

l

l

 

b

e

 

w

i

l

l

i

n

g

 

t

o

 

d

o

 

i

t

 

f

o

r

 

m

a

t

e

r

i

a

l

 

r

i

c

h

e

s

.

 

P

r

i

c

e

l

e

s

s

 

t

r

e

a

s

u

r

e

s

 

a

r

e

 

s

t

o

r

e

d

 

i

n

 

t

h

e

 

t

o

m

b

,

 

y

o

u

r

s

 

f

o

r

 

t

h

e

 

t

a

k

i

n

g

,

 

o

n

c

e

 

y

o

u

 

a

r

e

 

i

n

s

i

d

e

 

a

n

d

 

h

a

v

e

 

r

e

l

e

a

s

e

d

 

T

h

e

 

S

l

e

e

p

e

r

.




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

t

a

l

i

s

m

a

n

`







>

*

*

J

a

l

e

d

 

D

a

r

-

s

 

s

h

a

d

e

 

s

a

y

s

:

*

*

 

S

o

n

t

a

l

a

k

,

 

L

e

n

d

i

n

i

a

r

a

,

 

K

l

a

n

d

i

c

a

r

,

 

Y

e

l

i

n

a

k

,

 

a

n

d

 

Z

l

a

n

d

i

c

a

r

 

a

r

e

 

a

l

l

 

t

h

a

t

 

a

r

e

 

l

e

f

t

 

a

l

i

v

e

 

o

f

 

t

h

o

s

e

 

w

h

o

 

w

e

r

e

 

i

n

v

o

l

v

e

d

 

i

n

 

t

h

e

 

s

e

a

l

i

n

g

 

o

f

 

t

h

e

 

t

o

m

b

.

 

E

a

c

h

 

h

a

s

 

a

 

t

a

l

i

s

m

a

n

.

 

B

r

i

n

g

 

m

e

 

a

n

y

 

o

n

e

 

o

f

 

t

h

e

s

e

 

i

t

e

m

s

,

 

o

r

 

a

 

l

a

r

g

e

 

e

n

o

u

g

h

 

p

i

e

c

e

 

f

r

o

m

 

o

n

e

 

o

f

 

t

h

e

 

t

a

l

i

s

m

a

n

s

 

f

r

o

m

 

a

 

d

e

a

d

 

f

i

r

s

t

 

b

r

o

o

d

,

 

a

n

d

 

I

 

s

h

a

l

l

 

u

n

l

o

c

k

 

i

t

s

 

p

o

w

e

r

,

 

w

h

i

c

h

 

w

i

l

l

 

a

l

l

o

w

 

y

o

u

 

e

n

t

r

y

 

i

n

t

o

 

t

h

e

 

t

o

m

b

.




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

t

r

e

a

s

u

r

e

`







>

*

*

J

a

l

e

d

 

D

a

r

-

s

 

s

h

a

d

e

 

s

a

y

s

:

*

*

 

W

e

a

p

o

n

s

,

 

a

r

m

o

r

,

 

t

o

m

e

s

 

o

f

 

g

r

e

a

t

 

p

o

w

e

r

,

 

a

n

d

 

m

o

r

e

,

 

a

r

e

 

h

e

l

d

 

i

n

s

i

d

e

.

 

T

h

e

 

b

a

r

r

i

e

r

 

t

h

a

t

 

k

e

e

p

s

 

T

h

e

 

S

l

e

e

p

e

r

 

i

n

 

h

i

s

 

s

t

a

t

e

 

o

f

 

s

l

u

m

b

e

r

 

a

l

s

o

 

w

a

r

d

s

 

t

h

e

 

t

r

e

a

s

u

r

e

.

 

Y

o

u

 

m

u

s

t

 

f

i

r

s

t

 

r

e

m

o

v

e

 

t

h

i

s

 

b

a

r

r

i

e

r

.




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

b

a

r

r

i

e

r

`







>

*

*

J

a

l

e

d

 

D

a

r

-

s

 

s

h

a

d

e

 

s

a

y

s

:

*

*

 

F

o

u

r

 

d

r

a

g

o

n

s

 

m

a

i

n

t

a

i

n

 

t

h

e

 

b

a

r

r

i

e

r

 

a

r

o

u

n

d

 

T

h

e

 

S

l

e

e

p

e

r

.

 

T

h

e

s

e

 

f

o

u

r

 

d

r

a

g

o

n

s

 

c

h

a

n

n

e

l

 

t

h

e

i

r

 

e

n

e

r

g

i

e

s

 

i

n

t

o

 

t

h

e

 

b

a

r

r

i

e

r

.

 

F

o

r

 

t

h

e

 

b

a

r

r

i

e

r

 

t

o

 

d

r

o

p

,

 

y

o

u

 

m

u

s

t

 

s

l

a

y

 

a

l

l

 

f

o

u

r

.

 

T

h

i

s

 

w

i

l

l

 

b

e

 

n

o

 

e

a

s

y

 

t

a

s

k

,

 

f

o

r

 

t

h

e

y

 

a

r

e

 

p

o

w

e

r

f

u

l

 

a

n

d

 

l

e

a

r

n

e

d

,

 

t

h

e

 

b

e

s

t

 

a

n

d

 

b

r

i

g

h

t

e

s

t

 

o

f

 

t

h

a

t

 

e

r

a

.

 

B

u

t

 

o

n

c

e

 

t

h

i

s

 

i

s

 

d

o

n

e

,

 

T

h

e

 

S

l

e

e

p

e

r

 

s

h

a

l

l

 

a

w

a

k

e

,

 

a

n

d

 

t

h

e

 

t

r

e

a

s

u

r

e

s

 

t

h

e

r

e

 

s

h

a

l

l

 

b

e

 

y

o

u

r

s

 

f

o

r

 

t

h

e

 

t

a

k

i

n

g

.

 

T

h

e

 

S

l

e

e

p

e

r

 

w

i

l

l

 

t

r

a

v

e

l

 

t

o

 

t

h

e

 

S

k

y

s

h

r

i

n

e

 

t

o

 

r

e

s

u

m

e

 

h

i

s

 

r

i

g

h

t

f

u

l

 

p

o

s

i

t

i

o

n

 

a

m

o

n

g

 

w

u

r

m

k

i

n

d

.



















#

#

 

T

u

r

n

-

I

n

s










i

f

(

 

*

*

Y

o

u

 

t

u

r

n

 

i

n

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

1

0

6

7

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

9

2

9

6

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

9

2

9

6

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

S

h

a

r

d

 

o

f

 

H

s

a

g

r

a

'

s

 

T

a

l

i

s

m

a

n

<

/

a

>

 

 

o

r




 

*

*

Y

o

u

 

t

u

r

n

 

i

n

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

5

1

0

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

2

7

2

5

5

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

2

7

2

5

5

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

K

l

a

n

d

i

c

a

r

'

s

 

T

a

l

i

s

m

a

n

<

/

a

>

 

 

o

r




 

*

*

Y

o

u

 

t

u

r

n

 

i

n

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

5

1

0

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

2

7

2

5

6

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

2

7

2

5

6

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

S

o

n

t

a

l

a

k

'

s

 

T

a

l

i

s

m

a

n

<

/

a

>

 

 

o

r




 

*

*

Y

o

u

 

t

u

r

n

 

i

n

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

5

1

0

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

2

7

2

5

8

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

2

7

2

5

8

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

Z

l

a

n

d

i

c

a

r

'

s

 

T

a

l

i

s

m

a

n

<

/

a

>

 

 

o

r




 

*

*

Y

o

u

 

t

u

r

n

 

i

n

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

5

1

0

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

2

7

2

5

9

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

2

7

2

5

9

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

L

e

n

d

i

n

i

a

r

a

'

s

 

T

a

l

i

s

m

a

n

<

/

a

>

 

 

o

r




 

*

*

Y

o

u

 

t

u

r

n

 

i

n

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

5

1

0

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

2

7

2

6

6

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

2

7

2

6

6

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

Y

e

l

i

n

a

k

'

s

 

T

a

l

i

s

m

a

n

<

/

a

>

 

)

 

t

h

e

n




>

*

*

J

a

l

e

d

 

D

a

r

-

s

 

s

h

a

d

e

 

s

a

y

s

:

*

*

 

V

e

r

y

 

w

e

l

l

 

d

o

n

e

.

 

H

e

r

e

 

i

s

 

h

o

w

 

y

o

u

 

u

n

l

o

c

k

 

t

h

e

 

e

n

t

r

y

.

 

S

e

e

k

 

o

u

t

 

a

 

g

r

e

a

t

 

d

r

a

g

o

n

 

s

t

a

t

u

e

 

i

n

 

t

h

e

 

E

a

s

t

e

r

n

 

W

a

s

t

e

s

,

 

a

n

d

 

u

s

e

 

t

h

i

s

 

k

e

y

 

t

h

e

r

e

.

 

N

o

t

 

v

e

r

y

 

d

i

f

f

e

r

e

n

t

 

f

r

o

m

 

h

o

w

 

y

o

u

 

e

n

t

e

r

e

d

 

m

y

 

o

l

d

 

d

o

m

a

i

n

,

 

V

e

e

s

h

a

n

'

s

 

P

e

a

k

,

 

n

o

w

,

 

i

s

 

i

t

?

 

H

a

h

a

,

 

y

e

s

,

 

I

 

k

n

o

w

 

m

a

n

y

 

t

h

i

n

g

s

,

 

e

v

e

n

 

d

e

a

d

.




 

&

#

1

2

7

8

7

3

;

 

*

*

Y

o

u

 

r

e

c

e

i

v

e

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

1

0

8

0

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

2

7

2

6

5

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

2

7

2

6

5

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

S

l

e

e

p

e

r

'

s

 

K

e

y

<

/

a

>

 

(

+

5

0

0

0

0

 

e

x

p

)







 







*

*

T

h

i

s

 

N

P

C

 

*

s

h

o

u

l

d

*

 

r

e

t

u

r

n

 

i

n

c

o

r

r

e

c

t

 

i

t

e

m

s

 

g

i

v

e

n

.

*

*





