# tormented wraith

[tormented wraith](/npc/201055) is a level 44 Shade Warrior that spawns in [Plane of Justice](/zone/201).

Their primary faction is [KOS](/faction/5017).











#

#

 

D

i

a

l

o

g




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

N

P

C

T

y

p

e

I

D

(

)

 

=

=

 

2

0

1

0

5

5

 

)

 

t

h

e

n




>

*

t

o

r

m

e

n

t

e

d

 

w

r

a

i

t

h

 

g

l

a

r

e

s

 

a

t

 

y

o

u

 

a

n

d

 

d

o

e

s

 

n

o

t

 

r

e

s

p

o

n

d

.

*




e

l

s

e




>

*

t

o

r

m

e

n

t

e

d

 

w

r

a

i

t

h

 

w

a

i

l

s

,

 

s

e

n

d

i

n

g

 

a

 

c

h

i

l

l

 

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

 

y

o

u

r

 

b

o

n

e

s

.

*



















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

N

P

C

T

y

p

e

I

D

(

)

 

=

=

 

2

0

1

0

5

5

 

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

 

s

p

a

w

n

I

d

 

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

I

D

(

)

;




l

o

c

a

l

 

r

o

l

l

 

=

 

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

0

,

 

9

9

)

;




l

o

c

a

l

 

t

;







i

f

 

(

 

s

p

a

w

n

I

d

 

=

=

 

3

4

5

5

7

9

 

)

 

t

h

e

n




t

 

=

 

2

0

1

3

3

6

;

 




e

l

s

e

i

f

 

(

 

s

p

a

w

n

I

d

 

=

=

 

3

4

5

5

9

1

 

)

 

t

h

e

n




t

 

=

 

2

0

1

4

4

0

;

 




e

l

s

e

i

f

 

(

 

s

p

a

w

n

I

d

 

=

=

 

3

4

5

5

9

2

 

)

 

t

h

e

n




t

 

=

 

2

0

1

4

4

1

;

 










i

f

 

(

 

r

o

l

l

 

<

 

5

0

 

)

 

t

h

e

n




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

 

1

0

0

,

 

0

,

 

"

A

s

 

t

h

e

 

s

h

a

d

e

 

r

e

c

e

i

v

e

s

 

a

 

k

i

l

l

i

n

g

 

b

l

o

w

,

 

i

t

s

 

w

e

a

k

e

n

e

d

 

f

o

r

m

 

f

a

l

l

s

 

t

o

 

t

h

e

 

g

r

o

u

n

d

,

 

i

d

l

e

 

a

n

d

 

s

t

i

l

l

.

"

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

t

,

0

,

0

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

)

;




e

l

s

e




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

 

1

0

0

,

 

0

,

 

"

A

s

 

t

h

e

 

s

h

a

d

e

 

r

e

c

e

i

v

e

s

 

a

 

k

i

l

l

i

n

g

 

b

l

o

w

,

 

i

t

s

 

i

m

a

g

e

 

w

a

v

e

r

s

 

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

,

 

w

e

a

k

e

n

e

d

,

 

t

h

e

n

 

f

a

d

e

s

 

a

w

a

y

,

 

u

n

a

b

l

e

 

t

o

 

m

a

i

n

t

a

i

n

 

i

t

s

 

f

o

r

m

.

"

)

;








