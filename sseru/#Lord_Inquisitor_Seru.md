# Lord Inquisitor Seru

[Lord Inquisitor Seru](/npc/159000) is a level 66 Seru Warrior that spawns in [Sanctus Seru](/zone/159).

Their primary faction is [Seru](/faction/1483).l

o

c

a

l

 

S

p

a

w

n

X

 

=

 

0

;




l

o

c

a

l

 

S

p

a

w

n

Y

 

=

 

0

;




l

o

c

a

l

 

S

p

a

w

n

Z

 

=

 

0

;




l

o

c

a

l

 

S

p

a

w

n

H

 

=

 

0

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




S

p

a

w

n

X

 

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




S

p

a

w

n

Y

 

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




S

p

a

w

n

Z

 

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




S

p

a

w

n

H

 

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

e

a

d

i

n

g

(

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

k

i

l

l

(

1

1

,

 

2

5

0

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

 

L

o

r

d

 

I

n

q

u

i

s

i

t

o

r

 

S

e

r

u

 

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

g

o

b

a

c

k

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

g

o

b

a

c

k

*




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

S

p

a

w

n

X

,

S

p

a

w

n

Y

,

S

p

a

w

n

Z

,

S

p

a

w

n

H

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

g

o

b

a

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

X

(

)

 

<

 

-

3

6

4

 

o

r

 

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

 

>

 

-

1

0

0

 

o

r

 

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

 

<

 

-

5

6

4

 

o

r

 

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

 

>

 

-

3

0

0

)

 

t

h

e

n




*

*

L

o

r

d

 

I

n

q

u

i

s

i

t

o

r

 

S

e

r

u

 

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

N

o

!

 

I

 

m

u

s

t

 

n

o

t

 

l

e

a

v

e

 

t

h

e

 

t

i

m

e

 

c

h

a

m

b

e

r

!

 

I

f

 

I

 

d

o

,

 

I

'

l

l

 

a

g

e

 

a

n

d

 

d

i

e

!

<

/

s

p

a

n

>




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

S

p

a

w

n

X

,

S

p

a

w

n

Y

,

S

p

a

w

n

Z

,

S

p

a

w

n

H

)

;




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

A

l

l

(

)

;




*

*

L

o

r

d

 

I

n

q

u

i

s

i

t

o

r

 

S

e

r

u

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

H

e

a

l

(

)

;








