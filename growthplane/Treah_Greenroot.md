# Treah Greenroot

[Treah Greenroot](/npc/127021) is a level 60 Treant Druid that spawns in [Plane of Growth](/zone/127).

Their primary faction is [Servants of Tunare](/faction/438).





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

r

e

a

h

 

G

r

e

e

n

r

o

o

t

 

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




c

a

l

l

_

z

o

n

e

_

t

o

_

a

s

s

i

s

t

(

e

.

s

e

l

f

,

e

.

o

t

h

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

o

m

e

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

o

m

e

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

o

m

e

"

)

 

t

h

e

n




*

*

T

r

e

a

h

 

G

r

e

e

n

r

o

o

t

 

s

h

o

u

t

s

:

*

*

 

<

s

p

a

n

 

c

l

a

s

s

=

"

t

e

x

t

-

d

a

n

g

e

r

"

>

S

y

l

v

a

n

 

p

r

o

t

e

c

t

o

r

s

,

 

t

h

e

 

g

l

a

d

e

s

 

c

a

l

l

 

f

o

r

 

y

o

u

r

 

a

i

d

!

<

/

s

p

a

n

>




c

a

l

l

_

z

o

n

e

_

t

o

_

a

s

s

i

s

t

(

e

.

s

e

l

f

,

e

.

o

t

h

e

r

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

 

c

a

l

l

_

z

o

n

e

_

t

o

_

a

s

s

i

s

t

(

e

_

s

e

l

f

,

e

_

o

t

h

e

r

)







l

o

c

a

l

 

s

h

o

w

_

d

e

b

u

g

 

=

 

f

a

l

s

e

;







l

o

c

a

l

 

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

;







l

o

c

a

l

 

i

n

c

l

u

d

e

_

n

p

c

_

l

i

s

t

 

=

 

S

e

t

 

{

1

2

7

0

5

3

}

;

 




l

o

c

a

l

 

n

p

c

_

l

i

s

t

 

=

 

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

:

G

e

t

N

P

C

L

i

s

t

(

)

;




i

f

 

(

n

p

c

_

l

i

s

t

 

~

=

 

n

i

l

)

 

t

h

e

n




f

o

r

 

n

p

c

 

i

n

 

n

p

c

_

l

i

s

t

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

i

n

c

l

u

d

e

_

n

p

c

_

l

i

s

t

[

n

p

c

:

G

e

t

N

P

C

T

y

p

e

I

D

(

)

]

 

~

=

 

n

i

l

)

 

t

h

e

n







i

f

 

(

n

p

c

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




n

p

c

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

_

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

_

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

_

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




i

f

 

(

s

h

o

w

_

d

e

b

u

g

)

 

t

h

e

n

 

e

_

o

t

h

e

r

:

M

e

s

s

a

g

e

(

4

,

"

N

P

C

I

D

:

 

"

 

.

.

 

n

p

c

:

G

e

t

N

P

C

T

y

p

e

I

D

(

)

 

.

.

 

"

 

i

s

 

v

a

l

i

d

,

 

a

d

d

i

n

g

 

h

a

t

e

 

o

n

 

"

 

.

.

 

n

p

c

:

G

e

t

N

a

m

e

(

)

 

.

.

 

"

.

"

)

;

 

e

n

d




e

l

s

e




i

f

 

(

s

h

o

w

_

d

e

b

u

g

)

 

t

h

e

n

 

e

_

o

t

h

e

r

:

M

e

s

s

a

g

e

(

4

,

"

N

P

C

I

D

:

 

"

 

.

.

 

n

p

c

:

G

e

t

N

P

C

T

y

p

e

I

D

(

)

 

.

.

 

"

 

i

s

 

i

n

v

a

l

i

d

,

 

u

n

a

b

l

e

 

t

o

 

a

d

d

 

h

a

t

e

 

o

n

 

"

 

.

.

 

n

p

c

:

G

e

t

N

a

m

e

(

)

 

.

.

 

"

.

"

)

;

 

e

n

d







e

l

s

e




i

f

 

(

s

h

o

w

_

d

e

b

u

g

)

 

t

h

e

n

 

e

_

o

t

h

e

r

:

M

e

s

s

a

g

e

(

4

,

"

N

P

C

I

D

:

 

"

 

.

.

 

n

p

c

:

G

e

t

N

P

C

T

y

p

e

I

D

(

)

 

.

.

 

"

 

i

s

 

e

x

c

l

u

d

e

d

,

 

n

o

t

 

a

d

d

i

n

g

 

h

a

t

e

 

o

n

 

"

 

.

.

 

n

p

c

:

G

e

t

N

a

m

e

(

)

 

.

.

 

"

.

"

)

;

 

e

n

d

























f

u

n

c

t

i

o

n

 

S

e

t

 

(

l

i

s

t

)




l

o

c

a

l

 

s

e

t

 

=

 

{

}




f

o

r

 

_

,

 

l

 

i

n

 

i

p

a

i

r

s

(

l

i

s

t

)

 

d

o

 

s

e

t

[

l

]

 

=

 

t

r

u

e

 

e

n

d




r

e

t

u

r

n

 

s

e

t


