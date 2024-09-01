# Xanamech Nezmirthafen

[Xanamech Nezmirthafen](/npc/206208) is a level 66 Dragon Warrior that spawns in [Plane of Innovation](/zone/206).

Their primary faction is [KOS Plane of Innovation](/faction/5030).





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

A

p

p

e

a

r

a

n

c

e

(

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

w

a

k

e

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

l

i

e

*

 

f

o

r

 

0

 

s

e

c

o

n

d

s




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

8

0

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

X

a

n

a

m

e

c

h

 

N

e

z

m

i

r

t

h

a

f

e

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

l

i

e

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

S

e

t

A

p

p

e

a

r

a

n

c

e

(

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

t

i

m

e

r

 

=

=

 

"

w

a

k

e

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

S

e

t

S

p

e

c

i

a

l

A

b

i

l

i

t

y

(

2

4

,

 

0

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

e

t

S

p

e

c

i

a

l

A

b

i

l

i

t

y

(

2

5

,

 

0

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

e

t

S

p

e

c

i

a

l

A

b

i

l

i

t

y

(

3

5

,

 

0

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

e

t

B

o

d

y

T

y

p

e

(

5

,

 

f

a

l

s

e

)

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

 

 

X

a

n

a

m

e

c

h

 

N

e

z

m

i

r

t

h

a

f

e

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

N

i

t

r

a

m

 

A

n

i

z

o

k

]

(

/

n

p

c

/

2

0

6

0

3

3

)


