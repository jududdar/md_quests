# Ember

[Ember](/npc/33065) is a level 1 Beetle Warrior that spawns in [Misty Thicket](/zone/33).

Their primary faction is [Merchants of Rivervale](/faction/292).





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

f

o

l

l

o

w

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

f

o

l

l

o

w

"

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

 

o

p

p

o

n

e

n

t

I

D

 

=

 

3

3

0

6

6

;




l

o

c

a

l

 

m

o

b

t

y

p

e

I

D

 

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

o

p

p

o

n

e

n

t

I

D

)

;







i

f

(

m

o

b

t

y

p

e

I

D

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

 

f

o

l

l

o

w

_

m

o

b

 

=

 

m

o

b

t

y

p

e

I

D

:

G

e

t

I

D

(

)

;




e

q

.

f

o

l

l

o

w

(

f

o

l

l

o

w

_

m

o

b

,

1

0

)

;




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

f

o

l

l

o

w

*






















#

#

 

S

i

g

n

a

l

s




>

*

E

m

b

e

r

 

c

l

i

c

k

s

 

a

t

 

B

l

i

x

k

i

n

 

h

a

p

p

i

l

y

.

*




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

B

l

i

x

k

i

n

 

E

n

t

o

p

o

p

]

(

/

n

p

c

/

3

3

0

6

6

)


