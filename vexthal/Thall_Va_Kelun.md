# Thall Va Kelun

[Thall Va Kelun](/npc/158439) is a level 66 Akheva Rogue that spawns in [Vex Thal](/zone/158).

Their primary faction is [KOS](/faction/5017).





l

o

c

a

l

 

Z

_

L

E

V

E

L

 

=

 

1

0

0

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

 

 

T

h

a

l

l

 

V

a

 

K

e

l

u

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

a

t

_

c

h

e

c

k

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

c

h

e

a

t

_

c

h

e

c

k

*




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

k

i

l

l

_

p

l

a

y

e

r

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

c

h

e

a

t

_

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

Z

(

)

 

<

 

Z

_

L

E

V

E

L

 

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

k

i

l

l

_

p

l

a

y

e

r

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

T

h

a

l

l

 

V

a

 

K

e

l

u

n

 

c

a

s

t

s

:

*

*

 

[

D

e

s

t

r

o

y

]

(

/

s

p

e

l

l

/

1

9

4

8

)

 

o

n

 

t

h

e

m

s

e

l

v

e

s

.










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

k

i

l

l

_

p

l

a

y

e

r

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

 

h

l

 

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

H

a

t

e

L

i

s

t

(

)

;




f

o

r

 

e

n

t

 

i

n

 

h

l

.

e

n

t

r

i

e

s

 

d

o




i

f

 

(

 

e

n

t

.

e

n

t

:

I

s

C

l

i

e

n

t

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

C

a

s

t

S

p

e

l

l

(

9

8

2

,

 

e

n

t

.

e

n

t

:

G

e

t

I

D

(

)

,

 

0

,

 

1

)

;

 




r

e

t

u

r

n

;











