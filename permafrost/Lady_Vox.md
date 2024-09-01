# Lady Vox

[Lady Vox](/npc/73057) is a level 55 Dragon Cleric that spawns in [Permafrost Caverns](/zone/73).

Their primary faction is [Vox](/faction/319).l

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

a

d

y

 

V

o

x

 

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

1

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

1

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

1

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

4

3

1

 

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

8

5

 

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

 

7

7

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

 

>

 

1

0

9

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

Z

(

)

 

 

<

 

-

5

0

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

L

a

d

y

 

V

o

x

 

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

T

h

e

 

S

l

e

e

p

e

r

 

s

t

i

r

s

!

 

 

A

 

g

l

o

r

i

o

u

s

 

n

e

w

 

a

g

e

 

f

o

r

 

N

o

r

r

a

t

h

 

i

s

 

a

b

o

u

t

 

t

o

 

b

e

g

i

n

,

 

a

n

d

 

m

y

 

e

x

i

l

e

 

i

s

 

a

b

o

u

t

 

t

o

 

e

n

d

!

<

/

s

p

a

n

>





