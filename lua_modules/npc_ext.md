f

u

n

c

t

i

o

n

 

N

P

C

:

F

o

r

e

a

c

h

H

a

t

e

L

i

s

t

(

f

u

n

c

,

 

c

o

n

d

)




c

o

n

d

 

=

 

c

o

n

d

 

o

r

 

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

,

 

h

a

t

e

,

 

d

a

m

a

g

e

,

 

f

r

e

n

z

y

)

 

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

 

e

n

d

;




l

o

c

a

l

 

l

s

t

 

=

 

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

 

l

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




l

o

c

a

l

 

c

v

 

=

 

c

o

n

d

(

e

n

t

.

e

n

t

,

 

e

n

t

.

h

a

t

e

,

 

e

n

t

.

d

a

m

a

g

e

,

 

e

n

t

.

f

r

e

n

z

y

)

;




i

f

(

c

v

)

 

t

h

e

n




f

u

n

c

(

e

n

t

.

e

n

t

,

 

e

n

t

.

h

a

t

e

,

 

e

n

t

.

d

a

m

a

g

e

,

 

e

n

t

.

f

r

e

n

z

y

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

 

N

P

C

:

C

o

u

n

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

c

o

n

d

)




c

o

n

d

 

=

 

c

o

n

d

 

o

r

 

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

,

 

h

a

t

e

,

 

d

a

m

a

g

e

,

 

f

r

e

n

z

y

)

 

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

 

e

n

d

;




l

o

c

a

l

 

l

s

t

 

=

 

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




l

o

c

a

l

 

r

e

t

 

=

 

0

;




f

o

r

 

e

n

t

 

i

n

 

l

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




l

o

c

a

l

 

c

v

 

=

 

c

o

n

d

(

e

n

t

.

e

n

t

,

 

e

n

t

.

h

a

t

e

,

 

e

n

t

.

d

a

m

a

g

e

,

 

e

n

t

.

f

r

e

n

z

y

)

;




i

f

(

c

v

)

 

t

h

e

n




r

e

t

 

=

 

r

e

t

 

+

 

1

;













r

e

t

u

r

n

 

r

e

t

;













f

u

n

c

t

i

o

n

 

N

P

C

:

C

h

e

c

k

G

r

o

u

n

d

(

r

a

n

g

e

)







l

o

c

a

l

 

i

d

,

 

i

x

,

 

i

y

,

 

i

z

;




l

o

c

a

l

 

s

x

,

 

s

y

,

 

s

z

 

=

 

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







l

o

c

a

l

 

o

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

:

G

e

t

O

b

j

e

c

t

L

i

s

t

(

)

;




r

a

n

g

e

 

=

 

t

o

n

u

m

b

e

r

(

r

a

n

g

e

)

 

o

r

 

2

5

;







f

o

r

 

o

b

j

 

i

n

 

o

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

x

,

 

i

y

,

 

i

z

 

=

 

o

b

j

:

G

e

t

X

(

)

,

 

o

b

j

:

G

e

t

Y

(

)

,

 

o

b

j

:

G

e

t

Z

(

)

;




i

f

 

(

 

o

b

j

:

G

e

t

I

t

e

m

I

D

(

)

 

>

 

0




a

n

d

 

i

x

 

-

 

s

x

 

<

 

r

a

n

g

e

 

a

n

d

 

i

x

 

-

 

s

x

 

>

 

-

r

a

n

g

e




a

n

d

 

i

y

 

-

 

s

y

 

<

 

r

a

n

g

e

 

a

n

d

 

i

y

 

-

 

s

y

 

>

 

-

r

a

n

g

e




a

n

d

 

i

z

 

-

 

s

z

 

<

 

r

a

n

g

e

 

a

n

d

 

i

z

 

-

 

s

z

 

>

 

-

r

a

n

g

e




)

 

t

h

e

n




o

b

j

:

D

e

p

o

p

W

i

t

h

T

i

m

e

r

(

)

;




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


