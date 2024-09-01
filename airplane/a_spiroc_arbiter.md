# a spiroc arbiter

[a spiroc arbiter](/npc/71008) is a level 52 Aviak Druid that spawns in [Plane of Sky](/zone/71).

Their primary faction is [KOS](/faction/5017).l

o

c

a

l

 

a

r

r

i

v

e

 

=

 

f

a

l

s

e

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

a

 

s

p

i

r

o

c

 

v

a

n

q

u

i

s

h

e

r

]

(

/

n

p

c

/

7

1

0

2

2

)
















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

b

a

n

i

s

h

e

r

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




a

r

r

i

v

e

 

=

 

t

r

u

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

b

a

n

i

s

h

e

r

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

 

n

o

t

 

a

r

r

i

v

e

 

o

r

 

e

.

s

e

l

f

:

I

s

E

n

g

a

g

e

d

(

)

 

o

r

 

e

.

s

e

l

f

:

C

h

a

r

m

e

d

(

)

 

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

;










i

f

 

(

 

n

o

t

 

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

a

 

s

p

i

r

o

c

 

b

a

n

i

s

h

e

r

]

(

/

n

p

c

/

7

1

0

0

7

)

 

)

 

t

h

e

n

 




*

*

S

p

a

w

n

 

N

P

C

 

f

r

o

m

 

s

p

a

w

n

 

g

r

o

u

p

:

*

*

 

 

U

n

k

n

o

w

n

 

N

P

C

 

w

i

t

h

 

i

d

:

 

3

6

4

3

1

4

.

 

a

f

t

e

r

 

1

 

s

e

c

o

n

d

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

 

 

a

 

s

p

i

r

o

c

 

a

r

b

i

t

e

r

 

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




a

r

r

i

v

e

 

=

 

f

a

l

s

e

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




a

r

r

i

v

e

 

=

 

t

r

u

e

;


