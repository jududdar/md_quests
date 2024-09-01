# Mildar Gormrok

[Mildar Gormrok](/npc/211039) is a level 60 Human Warrior that spawns in [Halls of Honor](/zone/211).

Their primary faction is [Battalion of Marr](/faction/1656).l

o

c

a

l

 

n

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

a

n

i

m

a

t

e

*




>

*

*

M

i

l

d

a

r

 

G

o

r

m

r

o

k

 

s

a

y

s

:

*

*

 

Y

e

s

 

s

i

r

!

 

S

e

r

g

e

a

n

t

 

B

r

y

s

o

n

,

 

s

i

r

!




e

.

s

e

l

f

:

M

o

v

e

T

o

(

-

1

3

3

7

,

 

1

5

0

,

 

7

.

5

,

 

6

5

,

 

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

s

i

g

n

a

l

 

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

M

i

l

d

a

r

 

G

o

r

m

r

o

k

 

s

a

y

s

:

*

*

 

S

i

r

!

 

Y

e

s

,

 

s

i

r

!







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

i

g

n

a

l

 

=

=

 

4

 

)

 

t

h

e

n




>

*

*

M

i

l

d

a

r

 

G

o

r

m

r

o

k

 

s

a

y

s

:

*

*

 

Y

e

s

 

s

i

r

!

 

S

e

r

g

e

a

n

t

 

B

r

y

s

o

n

,

 

s

i

r

!




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

o

v

e

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

i

g

n

a

l

 

=

=

 

5

 

)

 

t

h

e

n




>

*

*

M

i

l

d

a

r

 

G

o

r

m

r

o

k

 

s

a

y

s

:

*

*

 

L

e

t

 

u

s

 

s

p

a

r

!




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

a

n

i

m

a

t

e

*

 

f

o

r

 

1

 

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

a

n

i

m

a

t

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

e

t

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

,

 

6

0

0

0

0

)

;




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

o

a

n

i

m

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




n

 

=

 

0

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

o

a

n

i

m

"

 

)

 

t

h

e

n




n

 

=

 

n

 

+

 

1

;







l

o

c

a

l

 

a

n

i

m

 

=

 

1

;




i

f

 

(

 

n

 

=

=

 

2

 

)

 

t

h

e

n




a

n

i

m

 

=

 

3

;




e

l

s

e

i

f

 

(

 

n

 

=

=

 

3

 

)

 

t

h

e

n




a

n

i

m

 

=

 

1

1

;




e

l

s

e

i

f

 

(

 

n

 

=

=

 

4

 

)

 

t

h

e

n




a

n

i

m

 

=

 

7

;




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

D

o

A

n

i

m

(

a

n

i

m

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

t

i

m

e

r

 

=

=

 

"

m

o

v

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




e

.

s

e

l

f

:

M

o

v

e

T

o

(

-

1

3

1

0

,

 

2

0

9

,

 

7

.

5

,

 

4

2

.

8

3

2

8

6

,

 

t

r

u

e

)

;








