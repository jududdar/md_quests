# Keldor Dek`Torek

[Keldor Dek`Torek](/npc/113135) is a level 65 Giant Wizard that spawns in [Kael Drakkel](/zone/113).

Their primary faction is [King Tormax](/faction/429).





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

k

i

n

g

"

,

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

7

0

0

0

0

0

,

7

5

0

0

0

0

0

)

)

;




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

m

e

d

"

,

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

2

7

0

0

0

0

)

)

;
















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

K

e

l

d

o

r

 

D

e

k

-

T

o

r

e

k

 

c

o

n

t

i

n

u

e

s

 

t

o

 

d

o

 

w

h

a

t

 

h

e

 

w

a

s

 

d

o

i

n

g

 

b

e

f

o

r

e

 

y

o

u

 

a

t

t

e

m

p

e

d

 

t

o

 

i

n

t

e

r

r

u

p

t

 

h

i

m

.

*




e

l

s

e




*

*

K

e

l

d

o

r

 

D

e

k

-

T

o

r

e

k

 

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

e

d

"

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

E

m

o

t

e

(

e

q

.

C

h

o

o

s

e

R

a

n

d

o

m

(

"

'

s

 

e

y

e

s

 

g

l

o

w

 

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

.

"

,

"

s

e

e

m

s

 

t

o

 

b

e

 

c

o

n

c

e

n

t

r

a

t

i

n

g

 

o

n

 

a

 

f

a

r

 

o

f

f

 

p

l

a

c

e

.

"

,

"

w

h

i

s

p

e

r

s

,

 

'

V

e

l

k

e

t

o

r

.

.

.

 

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

 

w

a

t

c

h

i

n

g

.

'

"

)

)

;




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

m

e

d

"

,

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

2

7

0

0

0

0

)

)

;







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

k

i

n

g

"

)

 

t

h

e

n




i

f

(

*

*

s

p

a

w

n

e

d

 

N

P

C

:

*

*

 

 

[

K

i

n

g

 

T

o

r

m

a

x

]

(

/

n

p

c

/

1

1

3

2

1

5

)

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

m

e

d

*




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

"

k

i

n

g

"

)




e

.

s

e

l

f

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

2

7

)

;




e

l

s

e




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

k

i

n

g

"

,

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

7

0

0

0

0

0

,

7

5

0

0

0

0

0

)

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

1

)

 

t

h

e

n




*

*

Z

o

n

e

 

W

i

d

e

 

E

m

o

t

e

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

w

a

r

n

i

n

g

"

>

*

K

e

l

d

o

r

 

D

e

k

'

 

T

o

r

e

k

 

s

a

y

s

 

'

G

r

e

e

t

i

n

g

s

 

m

y

 

l

o

r

d

.

 

I

 

h

a

v

e

 

b

e

e

n

 

d

e

e

p

 

i

n

 

m

e

d

i

t

a

t

i

o

n

 

a

n

d

 

h

a

v

e

 

s

o

m

e

 

n

e

w

s

 

w

h

i

c

h

 

y

o

u

 

m

i

g

h

t

 

f

i

n

d

 

m

o

s

t

 

i

n

t

e

r

e

s

t

i

n

g

.

'

*

<

/

s

p

a

n

>




*

*

Z

o

n

e

 

W

i

d

e

 

E

m

o

t

e

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

w

a

r

n

i

n

g

"

>

*

K

i

n

g

 

T

o

r

m

a

x

 

s

a

y

s

 

'

W

h

a

t

 

i

s

 

i

t

 

y

o

u

 

h

a

v

e

 

s

e

e

n

 

i

n

 

y

o

u

r

 

v

i

s

i

o

n

,

 

K

e

l

d

o

r

?

 

A

n

o

t

h

e

r

 

v

i

s

i

o

n

 

o

f

 

t

h

a

t

 

o

l

d

 

f

o

o

l

 

Y

e

l

n

i

a

k

?

'

*

<

/

s

p

a

n

>




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

 

1

2

)

 

t

h

e

n




*

*

Z

o

n

e

 

W

i

d

e

 

E

m

o

t

e

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

w

a

r

n

i

n

g

"

>

*

K

e

l

d

o

r

 

D

e

k

'

 

T

o

r

e

k

 

s

a

y

s

 

'

M

u

c

h

 

w

o

r

s

e

 

m

y

 

l

o

r

d

.

 

I

 

w

a

t

c

h

e

d

 

y

o

u

 

d

i

e

 

w

i

t

h

 

m

y

 

o

w

n

 

e

y

e

s

.

 

A

t

 

t

h

e

 

h

a

n

d

s

 

o

f

 

o

u

t

l

a

n

d

e

r

s

 

a

n

d

 

d

r

a

g

o

n

s

.

 

I

 

f

e

a

r

 

t

h

a

t

 

m

y

 

o

l

d

 

m

a

s

t

e

r

 

i

s

 

t

o

y

i

n

g

 

w

i

t

h

 

m

y

 

m

i

n

d

.

'

*

<

/

s

p

a

n

>




*

*

Z

o

n

e

 

W

i

d

e

 

E

m

o

t

e

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

w

a

r

n

i

n

g

"

>

*

K

i

n

g

 

T

o

r

m

a

x

 

s

a

y

s

 

'

T

h

a

t

 

f

o

o

l

 

V

e

l

k

e

t

o

r

?

 

G

e

t

 

a

 

h

o

l

d

 

o

f

 

y

o

u

r

s

e

l

f

,

 

K

e

l

d

o

r

.

 

 

Y

o

u

r

 

m

a

g

i

c

 

i

s

 

a

s

 

s

t

r

o

n

g

 

a

s

 

h

i

s

 

a

n

d

 

L

o

r

d

 

R

a

l

l

o

s

 

s

m

i

l

e

s

 

u

p

o

n

 

y

o

u

.

 

N

o

w

 

s

t

o

p

 

t

h

i

s

 

n

o

n

s

e

n

s

e

 

o

f

 

V

e

l

k

e

t

o

r

,

 

h

e

 

i

s

 

m

o

r

e

 

a

 

t

h

r

e

a

t

 

t

o

 

t

h

e

 

C

o

l

d

a

i

n

 

t

h

a

n

 

h

e

 

i

s

 

t

o

 

m

e

.

 

I

 

c

a

s

t

 

h

i

m

 

o

u

t

 

o

f

 

t

h

i

s

 

c

i

t

y

 

o

n

c

e

 

a

n

d

 

I

 

c

o

u

l

d

 

s

t

r

i

k

e

 

h

i

m

 

d

o

w

n

 

a

g

a

i

n

 

i

f

 

n

e

e

d

 

b

e

.

'

*

<

/

s

p

a

n

>




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

 

1

3

)

 

t

h

e

n




*

*

Z

o

n

e

 

W

i

d

e

 

E

m

o

t

e

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

w

a

r

n

i

n

g

"

>

*

K

e

l

d

o

r

 

D

e

k

'

 

T

o

r

e

k

 

s

a

y

s

 

'

I

 

p

r

a

y

 

m

y

 

v

i

s

i

o

n

s

 

a

r

e

 

f

a

l

s

e

,

 

m

y

 

l

o

r

d

.

 

 

I

 

h

a

v

e

 

s

e

e

n

 

o

t

h

e

r

 

t

h

i

n

g

s

 

t

h

o

u

g

h

.

.

.

 

T

h

i

n

g

s

 

w

h

i

c

h

 

w

o

r

r

y

 

m

y

 

i

m

m

e

n

s

e

l

y

.

 

 

T

h

e

 

o

u

t

l

a

n

d

e

r

s

,

 

t

h

e

y

 

h

a

v

e

 

b

e

g

u

n

 

t

o

 

s

i

d

e

 

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

 

w

h

o

 

w

o

r

s

h

i

p

 

L

o

r

d

 

Z

e

k

 

h

a

v

e

 

f

o

r

s

a

k

e

n

 

h

i

m

.

 

I

 

s

u

g

g

e

s

t

 

t

h

a

t

 

y

o

 

h

a

v

e

 

t

h

e

 

t

e

m

p

l

e

 

o

f

 

L

o

r

d

 

Z

e

k

 

b

e

c

o

m

e

 

m

o

r

e

 

h

e

a

v

i

l

y

 

p

r

o

t

e

c

t

e

d

.

 

 

T

h

e

 

o

u

t

l

a

n

d

e

r

s

 

s

h

o

u

l

d

 

n

o

t

 

t

r

e

a

d

 

u

p

o

n

 

i

t

s

 

h

o

l

y

 

g

r

o

u

n

d

.

'

*

<

/

s

p

a

n

>




*

*

Z

o

n

e

 

W

i

d

e

 

E

m

o

t

e

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

w

a

r

n

i

n

g

"

>

*

K

i

n

g

 

T

o

r

m

a

x

 

s

a

y

s

 

'

S

o

 

i

t

 

w

i

l

l

 

b

e

 

t

h

e

n

.

 

 

T

h

e

 

h

a

l

l

s

 

o

f

 

t

h

e

 

g

r

e

a

t

 

t

e

m

p

l

e

 

o

f

 

R

a

l

l

o

s

 

Z

e

k

 

s

h

a

l

l

 

n

o

t

 

b

e

 

w

a

l

k

e

d

 

b

y

 

a

n

y

 

o

t

h

e

r

 

t

h

a

n

 

t

h

e

 

t

r

u

e

 

c

h

i

l

d

r

e

n

 

o

f

 

Z

e

k

,

 

t

h

e

 

g

i

a

n

t

s

.

 

 

W

e

 

w

i

l

l

 

h

a

v

e

 

t

o

 

w

o

r

k

 

h

a

r

d

e

r

 

t

o

 

r

e

c

r

u

i

t

 

o

u

t

l

a

n

d

e

r

s

 

i

n

t

o

 

o

u

r

 

s

e

r

v

i

c

e

 

a

s

 

w

e

l

l

.

 

 

I

f

 

w

e

 

a

r

e

 

t

o

 

w

i

p

e

 

t

h

e

 

d

r

a

g

o

n

s

 

f

r

o

m

 

t

h

e

 

f

a

c

e

 

o

f

 

V

e

l

i

o

u

s

 

w

e

 

w

i

l

l

 

n

e

e

d

 

h

u

n

d

r

e

d

s

 

o

f

 

p

o

w

e

r

f

u

l

 

m

e

r

c

e

n

a

r

i

e

s

 

t

o

 

f

i

g

h

t

 

a

l

o

n

g

 

s

i

d

e

 

u

s

.

'

*

<

/

s

p

a

n

>




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

 

1

4

)

 

t

h

e

n




*

*

Z

o

n

e

 

W

i

d

e

 

E

m

o

t

e

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

w

a

r

n

i

n

g

"

>

*

K

e

l

d

o

r

 

D

e

k

'

 

T

o

r

e

k

 

s

a

y

s

 

'

H

o

w

 

s

h

a

l

l

 

w

e

 

e

n

t

i

c

e

 

t

h

e

 

o

u

t

l

a

n

d

e

r

s

 

i

n

t

o

 

o

u

r

 

s

e

r

v

i

c

e

 

m

y

 

l

o

r

d

?

'

*

<

/

s

p

a

n

>




*

*

Z

o

n

e

 

W

i

d

e

 

E

m

o

t

e

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

w

a

r

n

i

n

g

"

>

*

K

i

n

g

 

T

o

r

m

a

x

 

s

a

y

s

 

'

I

 

s

h

a

l

l

 

 

h

a

v

e

 

t

h

e

 

s

m

i

t

h

s

 

b

e

g

i

n

 

c

r

a

f

t

i

n

g

 

g

r

e

a

t

 

a

r

m

o

r

 

a

n

d

 

w

e

a

p

o

n

s

 

a

t

 

a

 

s

c

a

l

e

 

t

h

e

s

e

 

o

u

t

l

a

n

d

e

r

s

 

c

a

n

 

u

s

e

.

 

T

h

o

s

e

 

w

h

o

 

s

e

r

v

e

 

u

s

 

w

e

l

l

 

w

i

l

l

 

b

e

 

r

e

w

a

r

d

e

d

 

w

i

t

h

 

t

h

e

a

s

e

 

c

r

e

a

t

i

o

n

s

.

 

K

e

l

d

o

r

,

 

b

e

g

i

n

 

c

r

a

f

t

i

n

g

 

m

a

g

i

c

a

l

 

i

t

e

m

s

 

t

h

e

 

l

i

k

e

s

 

o

f

 

w

h

i

c

h

 

t

h

i

s

e

 

r

e

a

l

m

 

h

a

s

 

n

e

v

e

r

 

s

e

e

n

 

t

o

 

r

e

w

a

r

d

 

t

h

e

 

s

o

r

c

e

r

e

r

s

 

w

h

o

 

w

i

l

l

 

a

i

d

 

u

s

.

 

 

P

e

r

h

a

p

s

 

I

 

w

i

l

l

 

e

v

e

n

 

g

r

a

n

t

 

a

 

t

i

t

l

e

 

t

o

 

t

h

o

s

e

 

w

h

o

 

c

a

n

 

h

e

l

p

 

u

s

 

r

e

a

c

h

 

o

u

r

 

g

r

e

a

t

 

g

o

a

l

!

'

*

<

/

s

p

a

n

>




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

 

1

5

)

 

t

h

e

n




*

*

Z

o

n

e

 

W

i

d

e

 

E

m

o

t

e

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

w

a

r

n

i

n

g

"

>

*

K

e

l

d

o

r

 

D

e

k

'

 

T

o

r

e

k

 

s

a

y

s

 

'

I

 

w

i

l

l

 

b

e

g

i

n

 

a

t

 

o

n

c

e

 

m

y

 

l

o

r

d

.

 

M

a

y

 

R

a

l

l

o

s

 

s

m

i

l

e

 

u

p

o

n

 

u

s

 

a

l

l

.

'

*

<

/

s

p

a

n

>




*

*

Z

o

n

e

 

W

i

d

e

 

E

m

o

t

e

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

w

a

r

n

i

n

g

"

>

*

K

i

n

g

 

T

o

r

m

a

x

 

s

a

y

s

 

'

I

 

a

m

 

s

u

r

e

 

h

e

 

w

i

l

l

,

 

f

a

i

t

h

f

u

l

 

s

e

r

v

a

n

t

.

'

*

<

/

s

p

a

n

>




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

 

2

9

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

S

t

o

p

W

a

n

d

e

r

i

n

g

(

)

;




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

m

e

d

"

,

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

2

7

0

0

0

0

)

)

;




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

k

i

n

g

"

,

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

7

0

0

0

0

0

,

7

5

0

0

0

0

0

)

)

;





