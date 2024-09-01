# Barrel Barge

[Barrel Barge](/npc/840) is a level 50 Launch Warrior that spawns in [Oasis of Marr](/zone/37).





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




l

o

c

a

l

 

z

o

n

e

_

t

i

m

e

 

=

 

e

q

.

g

e

t

_

z

o

n

e

_

t

i

m

e

(

)

;




l

o

c

a

l

 

h

o

u

r

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

h

o

u

r

"

]

;




l

o

c

a

l

 

m

i

n

u

t

e

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

m

i

n

u

t

e

"

]

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

S

h

u

t

t

l

e

 

s

p

a

w

n

e

d

!

 

N

a

m

e

 

i

s

:

 

B

a

r

r

e

l

 

B

a

r

g

e

 

T

i

m

e

 

i

s

:

 

"

 

.

.

 

h

o

u

r

 

.

.

"

:

"

 

.

.

 

m

i

n

u

t

e

 

.

.

 

"

"

,

 

1

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

 

z

o

n

e

_

t

i

m

e

 

=

 

e

q

.

g

e

t

_

z

o

n

e

_

t

i

m

e

(

)

;




l

o

c

a

l

 

h

o

u

r

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

h

o

u

r

"

]

;




l

o

c

a

l

 

m

i

n

u

t

e

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

m

i

n

u

t

e

"

]

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

 

5

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

b

u

g

(

"

S

h

u

t

t

l

e

 

t

o

 

t

i

m

o

r

o

u

s

 

(

1

)

 

h

a

s

 

r

e

a

c

h

e

d

 

t

h

e

 

d

o

c

k

s

.

 

 

N

a

m

e

 

i

s

:

 

B

a

r

r

e

l

 

B

a

r

g

e

 

T

i

m

e

 

i

s

:

 

"

 

.

.

 

h

o

u

r

 

.

.

"

:

"

 

.

.

 

m

i

n

u

t

e

 

.

.

 

"

"

,

 

1

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

 

1

1

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

b

u

g

(

"

S

h

u

t

t

l

e

 

t

o

 

t

i

m

o

r

o

u

s

 

(

1

)

 

h

a

s

 

r

e

a

c

h

e

d

 

i

t

s

 

d

e

s

t

i

n

a

t

i

o

n

!

 

N

a

m

e

 

i

s

:

 

B

a

r

r

e

l

 

B

a

r

g

e

 

T

i

m

e

 

i

s

:

 

"

 

.

.

 

h

o

u

r

 

.

.

"

:

"

 

.

.

 

m

i

n

u

t

e

 

.

.

 

"

"

,

 

1

)

;




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

F

o

r

e

a

c

h

C

l

i

e

n

t

(




f

u

n

c

t

i

o

n

(

e

n

t

)




e

n

t

:

M

o

v

e

P

C

(

9

6

,

5

3

5

9

,

7

5

8

1

,

-

2

,

0

)

;




e

n

d

,




f

u

n

c

t

i

o

n

(

e

n

t

)




i

f

(

e

n

t

:

G

e

t

B

o

a

t

I

D

(

)

 

=

=

 

8

4

0

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







)

;





