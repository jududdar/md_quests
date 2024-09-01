# Kal`Vunar

[Kal`Vunar](/npc/124016) is a level 60 Drake Warrior that spawns in [Temple of Veeshan](/zone/124).

Their primary faction is [Guardians of Veeshan](/faction/467).











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

 

 

K

a

l

-

V

u

n

a

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

h

e

l

p

*

 

f

o

r

 

3

0

0

 

s

e

c

o

n

d

s




H

e

l

p

M

e

(

e

)

;




e

l

s

e




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

h

e

l

p

*



















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

h

e

l

p

"

)

 

t

h

e

n




H

e

l

p

M

e

(

e

)

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

e

l

p

M

e

(

e

)




l

o

c

a

l

 

a

a

r

y

o

n

a

r

 

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

M

o

b

B

y

N

p

c

T

y

p

e

I

D

(

1

2

4

0

1

0

)

;







i

f

 

(

a

a

r

y

o

n

a

r

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




a

a

r

y

o

n

a

r

:

C

a

s

t

T

o

N

P

C

(

)

:

M

o

v

e

T

o

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

,

 

f

a

l

s

e

)

;





