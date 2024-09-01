# Chronographer Muon

[Chronographer Muon](/npc/206044) is a level 70 Clockwork Golem Warrior that spawns in [Plane of Innovation](/zone/206).l

o

c

a

l

 

M

A

E

L

I

N

_

T

Y

P

E

 

=

 

2

0

6

2

0

9

;







f

u

n

c

t

i

o

n

 

H

a

s

I

t

e

m

I

n

v

O

n

l

y

(

c

l

i

e

n

t

,

 

i

t

e

m

i

d

)










f

o

r

 

i

 

=

 

0

,

 

3

0

,

 

1

 

d

o




l

o

c

a

l

 

t

h

i

s

i

t

e

m

 

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

t

e

m

I

D

A

t

(

i

)

;




i

f

(

t

h

i

s

i

t

e

m

 

=

=

 

i

t

e

m

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
















f

o

r

 

i

 

=

 

2

5

0

,

 

3

3

9

,

 

1

 

d

o




l

o

c

a

l

 

t

h

i

s

i

t

e

m

 

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

t

e

m

I

D

A

t

(

i

)

;




i

f

(

t

h

i

s

i

t

e

m

 

=

=

 

i

t

e

m

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

 

=

=

 

"

2

"

 

a

n

d

 

H

a

s

I

t

e

m

I

n

v

O

n

l

y

(

e

.

o

t

h

e

r

,

 

2

9

1

6

5

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

C

h

r

o

n

o

g

r

a

p

h

e

r

 

M

u

o

n

 

t

e

l

l

s

 

y

o

u

,

 

'

A

c

q

u

i

s

i

t

i

o

n

 

o

f

 

p

o

w

e

r

 

c

o

m

p

l

e

t

e

d

.

 

 

W

o

u

l

d

 

y

o

u

 

l

i

k

e

 

t

o

 

b

e

 

t

r

a

n

s

p

o

r

t

e

d

 

t

o

 

t

h

e

 

t

i

m

e

-

p

r

o

j

e

c

t

i

o

n

 

c

h

a

m

b

e

r

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

y

e

s

`







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

C

h

r

o

n

o

g

r

a

p

h

e

r

 

M

u

o

n

 

t

e

l

l

s

 

y

o

u

,

 

'

C

o

m

p

l

i

a

n

c

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

.

o

t

h

e

r

:

M

o

v

e

P

C

(

2

0

6

,

 

2

9

1

,

 

-

8

6

0

,

 

-

1

8

5

0

,

 

6

4

*

2

)

;




e

q

.

u

n

i

q

u

e

_

s

p

a

w

n

(

M

A

E

L

I

N

_

T

Y

P

E

,

 

0

,

 

0

,

 

7

6

3

,

 

-

8

3

7

,

 

-

1

8

8

7

.

1

2

2

,

 

1

8

4

)

;







e

l

s

e







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

C

h

r

o

n

o

g

r

a

p

h

e

r

 

M

u

o

n

 

t

e

l

l

s

 

y

o

u

,

 

'

G

r

e

e

t

i

n

g

 

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

d

.

 

 

I

 

h

a

v

e

 

n

o

 

u

s

e

 

f

o

r

 

y

o

u

 

a

t

 

t

h

i

s

 

t

i

m

e

.

 

 

G

o

o

d

 

b

y

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








