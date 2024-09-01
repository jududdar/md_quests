# Animated Decorin Blade

[Animated Decorin Blade](/npc/214310) is a level 57 Invisible Man Warrior that spawns in [Drunder, the Fortress of Zek](/zone/214).

Their primary faction is [The Diaku](/faction/1643).l

o

c

a

l

 

T

A

G

R

I

N

_

T

Y

P

E

 

=

 

2

1

4

0

5

4

;













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

 

1

2

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

i

m

a

t

e

d

 

D

e

c

o

r

i

n

 

B

l

a

d

e

 

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







l

o

c

a

l

 

m

o

b

 

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

T

A

G

R

I

N

_

T

Y

P

E

)

;




i

f

 

(

 

m

o

b

 

a

n

d

 

m

o

b

.

v

a

l

i

d

 

a

n

d

 

m

o

b

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

 

t

 

=

 

m

o

b

:

G

e

t

H

a

t

e

R

a

n

d

o

m

C

l

i

e

n

t

(

)

;




i

f

 

(

 

t

 

a

n

d

 

t

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




e

.

s

e

l

f

:

A

d

d

T

o

H

a

t

e

L

i

s

t

(

t

)

;

























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

i

m

a

t

e

d

 

D

e

c

o

r

i

n

 

B

l

a

d

e

 

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





