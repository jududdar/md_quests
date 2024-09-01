# Vhaksiz the Shade

[Vhaksiz the Shade](/npc/204028) is a level 65 Undead Knight Shadow Knight that spawns in [Plane of Nightmares](/zone/204).

Their primary faction is [KOS Plane of Nightmare](/faction/5029).l

o

c

a

l

 

x

,

 

y

,

 

z

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




x

 

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

X

(

)

;




y

 

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

Y

(

)

;




z

 

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

Z

(

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

 

 

V

h

a

k

s

i

z

 

t

h

e

 

S

h

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

e

a

s

h

c

h

e

c

k

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

l

e

a

s

h

c

h

e

c

k

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

l

e

a

s

h

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

C

a

l

c

u

l

a

t

e

D

i

s

t

a

n

c

e

(

x

,

 

y

,

 

z

)

 

>

 

1

5

5

 

)

 

t

h

e

n




*

*

V

h

a

k

s

i

z

 

t

h

e

 

S

h

a

d

e

*

*

 

c

l

e

a

r

s

 

h

a

t

e

 

l

i

s

t

.




e

.

s

e

l

f

:

G

M

M

o

v

e

(

x

,

 

y

,

 

z

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

S

p

a

w

n

P

o

i

n

t

H

(

)

)

;




*

*

V

h

a

k

s

i

z

 

t

h

e

 

S

h

a

d

e

 

c

a

s

t

s

:

*

*

 

[

A

n

n

u

l

 

S

e

l

f

]

(

/

s

p

e

l

l

/

2

8

3

0

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








