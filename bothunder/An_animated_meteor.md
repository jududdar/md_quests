# An animated meteor

[An animated meteor](/npc/209138) is a level 60 Dervish Warrior that spawns in [Bastion of Thunder](/zone/209).

Their primary faction is [KOS](/faction/5017).





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

A

n

 

a

n

i

m

a

t

e

d

 

m

e

t

e

o

r

 

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

 

 

A

n

 

a

n

i

m

a

t

e

d

 

m

e

t

e

o

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

Z

(

)

 

>

 

1

8

0

0

 

a

n

d

 

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




e

.

s

e

l

f

:

B

u

f

f

F

a

d

e

B

y

E

f

f

e

c

t

(

2

2

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

d

i

f

y

N

P

C

S

t

a

t

(

"

m

r

"

,

 

"

2

0

0

"

)

;





