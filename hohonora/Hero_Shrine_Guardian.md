# Hero Shrine Guardian

[Hero Shrine Guardian](/npc/211002) is a level 60 Human Warrior that spawns in [Halls of Honor](/zone/211).

Their primary faction is [Battalion of Marr](/faction/1656).





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

W

a

y

p

o

i

n

t

M

a

x

(

)

 

-

 

2

)

 

)

 

t

h

e

n




*

*

S

i

g

n

a

l

e

d

 

t

o

:

*

*

 

 

[

G

u

a

r

d

 

C

h

a

n

g

e

 

S

h

o

u

t

e

r

]

(

/

n

p

c

/

2

1

1

0

7

3

)







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

W

a

y

p

o

i

n

t

M

a

x

(

)

 

-

 

1

)

 

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

R

e

m

o

v

e

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

a

v

e

G

u

a

r

d

S

p

o

t

(

)

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

I

D

(

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

m

o

v

e

*

 

f

o

r

 

6

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

c

h

e

c

k

"

 

)

 

t

h

e

n




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

X

(

)

 

>

 

0

 

)

 

t

h

e

n




*

*

H

e

r

o

 

S

h

r

i

n

e

 

G

u

a

r

d

i

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

c

h

e

c

k

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

8

0

,

 

0

,

 

7

.

5

,

 

-

1

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

t

i

m

e

r

 

=

=

 

"

f

a

i

l

s

a

f

e

"

 

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

c

h

e

c

k

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

8

0

,

 

0

,

 

7

.

5

,

 

-

1

,

 

t

r

u

e

)

;





