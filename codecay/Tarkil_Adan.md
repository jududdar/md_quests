# Tarkil Adan

[Tarkil Adan](/npc/200267) is a level 1 Pusling Warrior that spawns in [The Crypt of Decay](/zone/200).

Their primary faction is [KOS](/faction/5017).l

o

c

a

l

 

M

A

X

_

K

E

Y

S

 

=

 

3

6

;







l

o

c

a

l

 

k

e

y

s

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

 

6

0

0

 

s

e

c

o

n

d

s




k

e

y

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




*

*

T

a

r

k

i

l

 

A

d

a

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

 

 

T

a

r

k

i

l

 

A

d

a

n

 

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










i

f

 

(

 

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

b

e

r

t

o

x

_

k

e

y

 

a

n

d

 

k

e

y

s

 

<

 

M

A

X

_

K

E

Y

S

 

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

T

a

r

k

i

l

 

A

d

a

n

 

l

e

t

s

 

o

u

t

 

a

 

g

r

o

a

n

 

a

n

d

 

t

h

e

n

 

w

h

i

m

p

e

r

s

 

s

a

y

i

n

g

,

 

'

Y

e

s

 

g

r

e

a

t

 

o

n

e

s

 

y

e

s

s

s

 

I

 

w

a

s

 

k

i

n

g

 

o

n

c

e

 

I

 

w

a

s

s

s

.

 

'

 

T

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

 

t

h

e

n

 

m

u

t

t

e

r

s

 

u

n

d

e

r

 

h

i

s

 

b

r

e

a

t

h

 

a

n

d

 

p

a

s

s

e

s

 

y

o

u

 

a

 

s

m

a

l

l

 

g

l

o

w

i

n

g

 

b

o

n

e

 

f

r

a

g

m

e

n

t

 

e

t

c

h

e

d

 

i

n

 

r

u

n

e

s

.

 

T

h

e

n

 

s

p

e

a

k

s

 

a

g

a

i

n

 

s

a

y

i

n

g

,

 

'

T

h

e

 

t

o

r

t

u

r

e

d

 

o

n

e

s

 

o

h

 

t

h

e

 

t

o

r

t

u

r

e

d

 

o

n

e

s

,

 

y

o

u

 

m

u

s

t

 

g

o

 

t

o

 

t

h

e

 

d

e

p

t

h

s

 

o

f

 

L

x

a

n

v

o

m

 

a

n

d

 

f

r

e

e

 

t

h

e

m

.

 

 

G

o

 

t

o

 

t

h

e

 

b

o

n

e

 

t

h

r

o

n

e

 

a

t

 

t

h

e

 

r

u

i

n

s

 

e

n

t

r

a

n

c

e

 

t

h

e

r

e

 

y

o

u

 

w

i

l

l

 

f

i

n

d

 

a

c

c

e

s

s

 

t

o

 

t

h

e

 

d

e

p

t

h

s

.

'

 

 

H

e

 

t

h

e

n

 

g

o

e

s

 

b

a

c

k

 

t

o

 

w

h

i

m

p

e

r

i

n

g

 

a

n

d

 

r

o

c

k

i

n

g

 

b

a

c

k

 

a

n

d

 

f

o

r

t

h

.

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

b

e

r

t

o

x

_

k

e

y

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







k

e

y

s

 

=

 

k

e

y

s

 

+

 

1

;











