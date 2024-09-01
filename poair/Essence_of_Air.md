# Essence of Air

[Essence of Air](/npc/215432) is a level 1 Elemental Warrior that spawns in [Plane of Air](/zone/215).l

o

c

a

l

 

F

L

A

G

_

L

I

M

I

T

 

=

 

7

2

;







l

o

c

a

l

 

f

l

a

g

s

 

=

 

0

;




l

o

c

a

l

 

r

i

d

,

 

g

i

d

,

 

c

i

d

;







f

u

n

c

t

i

o

n

 

C

l

i

e

n

t

C

a

n

F

l

a

g

(

m

o

b

)




i

f

 

(

 

m

o

b

:

I

s

C

l

i

e

n

t

(

)

 

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

 

c

l

i

e

n

t

 

=

 

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

C

l

i

e

n

t

(

)

;







l

o

c

a

l

 

r

a

i

d

 

=

 

c

l

i

e

n

t

:

G

e

t

R

a

i

d

(

)

;




l

o

c

a

l

 

g

r

o

u

p

 

=

 

c

l

i

e

n

t

:

G

e

t

G

r

o

u

p

(

)

;







i

f

 

(

 

r

i

d

 

a

n

d

 

r

a

i

d

.

v

a

l

i

d

 

a

n

d

 

r

a

i

d

:

G

e

t

I

D

(

)

 

=

=

 

r

i

d

 

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

 

g

i

d

 

a

n

d

 

g

r

o

u

p

.

v

a

l

i

d

 

a

n

d

 

g

r

o

u

p

:

G

e

t

I

D

(

)

 

=

=

 

g

i

d

 

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

 

c

i

d

 

a

n

d

 

c

l

i

e

n

t

:

G

e

t

I

D

(

)

 

=

=

 

c

i

d

 

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

 

t

r

u

e

;










r

e

t

u

r

n

 

f

a

l

s

e

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




r

i

d

,

 

g

i

d

,

 

c

i

d

 

=

 

n

i

l

,

 

n

i

l

,

 

n

i

l

;




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







l

o

c

a

l

 

r

a

i

d

 

=

 

c

l

i

e

n

t

:

G

e

t

R

a

i

d

(

)

;




l

o

c

a

l

 

g

r

o

u

p

 

=

 

c

l

i

e

n

t

:

G

e

t

G

r

o

u

p

(

)

;







i

f

 

(

 

r

a

i

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




r

i

d

 

=

 

r

a

i

d

:

G

e

t

I

D

(

)

;




e

l

s

e

i

f

 

(

 

g

r

o

u

p

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




g

i

d

 

=

 

g

r

o

u

p

:

G

e

t

I

D

(

)

;




e

l

s

e




c

i

d

 

=

 

c

l

i

e

n

t

:

G

e

t

I

D

(

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

"

F

l

a

g

g

e

r

 

N

P

C

 

w

i

l

l

 

a

c

k

n

o

w

l

e

d

g

e

 

"

.

.

c

l

i

e

n

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

'

s

 

r

a

i

d

/

g

r

o

u

p

;

 

R

a

i

d

 

I

D

 

=

=

 

"

.

.

(

r

i

d

 

o

r

 

"

(

n

i

l

)

"

)

.

.

"

;

 

 

G

r

o

u

p

 

I

D

 

=

=

 

"

.

.

(

g

i

d

 

o

r

 

"

(

n

i

l

)

"

)

,

 

1

)

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

 

1

2

0

0

 

s

e

c

o

n

d

s




f

l

a

g

s

 

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

 

 

E

s

s

e

n

c

e

 

o

f

 

A

i

r

 

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




e

q

.

p

a

u

s

e

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

)

;




e

l

s

e




e

q

.

r

e

s

u

m

e

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

E

s

s

e

n

c

e

 

o

f

 

A

i

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

 

(

 

n

o

t

 

*

*

Y

o

u

 

p

o

s

s

e

s

s

 

i

t

e

m

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

9

4

8

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

9

1

6

4

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

9

1

6

4

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

m

o

r

p

h

o

u

s

 

C

l

o

u

d

 

o

f

 

A

i

r

<

/

a

>

 

x

 

1




 

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

9

4

8

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

9

1

6

4

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

9

1

6

4

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

m

o

r

p

h

o

u

s

 

C

l

o

u

d

 

o

f

 

A

i

r

<

/

a

>




f

l

a

g

s

 

=

 

f

l

a

g

s

 

+

 

1

;










i

f

 

(

 

f

l

a

g

s

 

>

=

 

F

L

A

G

_

L

I

M

I

T

 

)

 

t

h

e

n




*

*

E

s

s

e

n

c

e

 

o

f

 

A

i

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








