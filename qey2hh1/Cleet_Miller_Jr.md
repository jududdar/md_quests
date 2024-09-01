# Cleet Miller Jr

[Cleet Miller Jr](/npc/12029) is a level 6 Human Shopkeeper that spawns in [Western Plains of Karana](/zone/12).

Their primary faction is [Karana Residents](/faction/345).





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

C

l

e

e

t

 

M

i

l

l

e

r

 

J

r

 

g

r

u

m

b

l

e

s

 

a

n

d

 

l

o

o

k

s

 

u

p

 

a

t

 

y

o

u

.

*




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

w

h

o

`







e

.

s

e

l

f

:

S

a

y

(

s

t

r

i

n

g

.

f

o

r

m

a

t

(

"

L

i

s

t

e

n

,

 

%

s

,

 

I

 

d

o

n

'

t

 

w

a

n

t

 

t

o

 

b

e

 

r

u

d

e

,

 

b

u

t

 

t

h

e

s

e

 

f

i

e

l

d

s

 

d

o

n

'

t

 

t

e

n

d

 

t

o

 

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

,

 

y

o

u

 

k

n

o

w

.

 

 

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

 

t

i

m

e

 

f

o

r

 

y

o

u

r

 

l

i

t

t

l

e

 

q

u

e

s

t

i

o

n

s

.

 

 

G

o

 

t

a

l

k

 

t

o

 

T

i

n

y

 

i

f

 

y

o

u

 

a

r

e

 

f

e

e

l

i

n

g

 

c

h

a

t

t

y

.

"

,

e

.

o

t

h

e

r

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




l

o

c

a

l

 

x

l

o

c

 

=

 

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

;




l

o

c

a

l

 

y

l

o

c

 

=

 

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

;




l

o

c

a

l

 

z

l

o

c

 

=

 

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

;







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

 

9

)

 

t

h

e

n




>

*

C

l

e

e

t

 

M

i

l

l

e

r

 

J

r

 

g

a

t

h

e

r

s

 

u

p

 

a

 

b

a

l

e

 

o

f

 

s

t

r

a

w

*




e

q

.

c

r

e

a

t

e

_

g

r

o

u

n

d

_

o

b

j

e

c

t

(

1

3

9

9

0

,

x

l

o

c

,

y

l

o

c

,

z

l

o

c

,

0

,

6

0

0

0

0

0

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

 

o

r

 

e

.

w

p

 

=

=

 

1

0

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

i

f

(

e

.

w

p

 

=

=

 

5

 

o

r

 

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





