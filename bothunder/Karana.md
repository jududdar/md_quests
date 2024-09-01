# Karana

[Karana](/npc/209136) is a level 75 Karana Warrior that spawns in [Bastion of Thunder](/zone/209).

Their primary faction is [The Rainkeeper](/faction/1619).l

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

 

3

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

K

a

r

a

n

a

 

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







l

o

c

a

l

 

q

g

l

o

b

a

l

s

 

=

 

e

q

.

g

e

t

_

q

g

l

o

b

a

l

s

(

e

.

o

t

h

e

r

)

;







i

f

 

(

 

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

e

.

o

t

h

e

r

)

 

)

 

t

h

e

n







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

K

a

r

a

n

a

 

s

a

y

s

:

*

*

 

K

a

r

a

n

a

 

l

o

o

k

s

 

d

o

w

n

 

a

t

 

S

o

a

n

d

s

o

'

s

 

f

a

c

e

.

 

 

H

e

 

s

e

e

m

s

 

s

o

 

i

n

s

i

g

n

i

f

i

c

a

n

t

 

n

e

x

t

 

t

o

 

t

h

e

 

m

a

s

s

i

v

e

 

s

t

a

t

u

r

e

 

o

f

 

t

h

e

 

R

a

i

n

k

e

e

p

e

r

.

 

 

'

D

o

n

'

t

 

w

o

r

r

y

 

m

o

r

t

a

l

,

 

A

s

k

r

 

i

s

 

u

n

h

a

r

m

e

d

,

 

I

 

h

a

v

e

 

s

e

t

 

h

i

m

 

o

n

 

a

 

j

o

u

r

n

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

 

t

a

k

e

 

h

i

m

 

t

o

 

a

l

l

 

c

o

r

n

e

r

s

 

o

f

 

t

h

i

s

 

r

e

a

l

i

t

y

.

 

 

H

e

 

w

i

l

l

 

e

i

t

h

e

r

 

f

i

n

d

 

t

h

e

 

b

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

 

F

a

l

l

e

n

 

o

r

 

h

e

 

w

i

l

l

 

d

i

e

 

t

r

y

i

n

g

.

 

 

A

n

d

 

w

h

a

t

 

o

f

 

y

o

u

 

c

h

a

m

p

i

o

n

s

?

 

 

D

o

 

y

o

u

 

w

i

s

h

 

t

o

 

f

o

l

l

o

w

 

t

h

e

 

p

a

t

h

 

o

f

 

t

h

e

 

F

a

l

l

e

n

?

 

 

A

 

m

o

r

e

 

d

a

n

g

e

r

o

u

s

 

p

a

t

h

 

h

a

s

 

n

e

v

e

r

 

e

x

i

s

t

e

d

.

 

 

D

e

f

y

 

t

h

e

 

w

i

l

l

 

o

f

 

t

h

e

 

P

a

n

t

h

e

o

n

 

a

t

 

y

o

u

r

 

p

e

r

i

l

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

f

o

l

l

o

w

 

t

h

e

 

p

a

t

h

 

o

f

 

t

h

e

 

F

a

l

l

e

n

`










l

o

c

a

l

 

k

a

r

a

n

a

 

=

 

t

o

n

u

m

b

e

r

(

q

g

l

o

b

a

l

s

.

k

a

r

a

n

a

 

o

r

 

0

)

;







i

f

 

(

 

k

a

r

a

n

a

 

=

=

 

3

 

)

 

t

h

e

n




*

*

M

e

s

s

a

g

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

a

r

a

n

a

 

b

e

g

i

n

s

 

t

o

 

l

a

u

g

h

 

q

u

i

e

t

l

y

.

 

 

Y

o

u

 

s

e

e

m

 

t

o

 

n

o

t

i

c

e

 

a

 

g

r

e

a

t

 

s

t

o

r

m

 

c

l

o

u

d

 

b

r

e

w

i

n

g

 

o

n

c

e

 

m

o

r

e

 

a

b

o

v

e

 

h

i

m

.

 

 

A

 

s

u

d

d

e

n

 

a

r

c

h

i

n

g

 

b

o

l

t

 

h

i

t

s

 

y

o

u

,

 

b

u

t

 

y

o

u

 

a

r

e

 

u

n

h

a

r

m

e

d

.

 

 

I

n

s

t

e

a

d

 

a

 

t

o

m

e

 

w

r

i

t

t

e

n

 

i

n

 

t

h

e

 

l

a

n

g

u

a

g

e

 

o

f

 

t

h

e

 

g

o

d

s

 

a

p

p

e

a

r

s

 

i

n

 

y

o

u

r

 

h

a

n

d

s

.

 

 

'

T

h

e

n

 

l

e

t

 

w

h

a

t

 

I

 

k

n

o

w

 

b

e

 

y

o

u

r

s

 

t

o

 

k

n

o

w

 

a

s

 

w

e

l

l

.

 

 

Y

o

u

r

 

p

a

t

h

 

l

e

a

d

s

 

y

o

u

 

o

n

w

a

r

d

 

S

o

a

n

d

s

o

.

 

 

T

h

e

 

p

a

t

h

 

t

o

 

p

o

w

e

r

 

o

r

 

r

u

i

n

,

 

t

h

e

 

c

h

o

i

c

e

 

i

s

 

u

p

 

t

o

 

y

o

u

.

 

 

S

p

e

a

k

 

t

h

e

 

w

o

r

d

s

 

a

n

d

 

I

 

w

i

l

l

 

s

e

n

d

 

y

o

u

 

o

n

 

y

o

u

r

 

w

a

y

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

q

.

s

e

t

_

g

l

o

b

a

l

(

"

k

a

r

a

n

a

"

,

 

"

4

"

,

 

5

,

 

"

F

"

)

;




*

*

M

e

s

s

a

g

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

Y

o

u

 

h

a

v

e

 

r

e

c

e

i

v

e

d

 

a

 

c

h

a

r

a

c

t

e

r

 

f

l

a

g

!

*

<

/

s

p

a

n

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

 

q

g

l

o

b

a

l

s

.

c

l

_

k

a

r

a

n

a

 

)

 

t

h

e

n




e

q

.

d

e

l

e

t

e

_

g

l

o

b

a

l

(

"

c

l

_

k

a

r

a

n

a

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

 

k

a

r

a

n

a

 

<

 

3

 

a

n

d

 

n

o

t

 

q

g

l

o

b

a

l

s

.

z

e

b

u

x

o

r

u

k

 

)

 

t

h

e

n




*

*

M

e

s

s

a

g

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

a

r

a

n

a

 

b

e

g

i

n

s

 

t

o

 

l

a

u

g

h

 

q

u

i

e

t

l

y

.

 

 

Y

o

u

 

s

e

e

m

 

t

o

 

n

o

t

i

c

e

 

a

 

g

r

e

a

t

 

s

t

o

r

m

 

c

l

o

u

d

 

b

r

e

w

i

n

g

 

o

n

c

e

 

m

o

r

e

 

a

b

o

v

e

 

h

i

m

.

 

 

'

Y

o

u

r

 

p

a

t

h

 

l

e

a

d

s

 

y

o

u

 

o

n

w

a

r

d

 

m

o

r

t

a

l

s

.

 

 

T

h

e

 

p

a

t

h

 

t

o

 

p

o

w

e

r

 

o

r

 

r

u

i

n

,

 

t

h

e

 

c

h

o

i

c

e

 

i

s

 

u

p

 

t

o

 

y

o

u

.

 

 

S

p

e

a

k

 

t

h

e

 

w

o

r

d

s

 

a

n

d

 

I

 

w

i

l

l

 

s

e

n

d

 

y

o

u

 

o

n

 

y

o

u

r

 

w

a

y

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

q

.

s

e

t

_

g

l

o

b

a

l

(

"

c

l

_

k

a

r

a

n

a

"

,

 

"

1

"

,

 

5

,

 

"

F

"

)

;




*

*

M

e

s

s

a

g

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

Y

o

u

 

h

a

v

e

 

r

e

c

e

i

v

e

d

 

a

 

n

e

w

 

c

h

e

c

k

l

i

s

t

 

f

l

a

g

!

*

<

/

s

p

a

n

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

e

n

d

 

m

e

`







>

*

K

a

r

a

n

a

 

n

o

d

s

 

a

n

d

 

b

e

g

i

n

s

 

t

o

 

u

t

t

e

r

 

t

h

e

 

s

a

m

e

 

u

n

f

a

m

i

l

i

a

r

 

w

o

r

d

s

 

t

h

a

t

 

s

e

n

t

 

A

s

k

r

 

i

n

t

o

 

t

h

e

 

v

o

i

d

.

 

 

T

h

e

 

s

t

o

r

m

 

a

b

o

v

e

 

h

i

m

 

r

i

s

e

s

 

u

p

 

a

n

d

 

b

e

g

i

n

s

 

t

o

 

s

p

a

r

k

 

s

e

n

d

i

n

g

 

c

h

i

l

l

s

 

u

p

 

y

o

u

r

 

s

p

i

n

e

.

 

 

T

h

e

 

R

a

i

n

k

e

e

p

e

r

'

s

 

v

o

i

c

e

 

r

i

s

e

s

 

t

o

 

a

n

 

i

n

c

r

e

d

i

b

l

e

 

w

a

i

l

 

a

s

 

t

h

e

 

s

t

o

r

m

 

r

a

g

e

s

 

t

h

r

o

u

g

h

 

t

h

e

 

r

o

o

m

.

 

 

T

h

e

 

c

o

l

d

 

r

a

i

n

 

p

e

l

t

i

n

g

 

y

o

u

r

 

f

a

c

e

 

i

s

 

t

h

e

 

l

a

s

t

 

t

h

i

n

g

 

y

o

u

 

r

e

m

e

m

b

e

r

 

a

s

 

a

 

g

r

e

a

t

 

b

o

l

t

 

o

f

 

p

u

r

e

 

s

t

o

r

m

 

e

n

e

r

g

y

 

e

n

v

e

l

o

p

e

s

 

y

o

u

.

*







*

*

K

a

r

a

n

a

 

c

a

s

t

s

:

*

*

 

[

G

a

t

e

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

6

)

 

o

n

 

t

a

r

g

e

t

.








