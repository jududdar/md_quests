# Lord Nagafen

[Lord Nagafen](/npc/32040) is a level 55 Dragon Warrior that spawns in [Nagafen's Lair](/zone/32).

Their primary faction is [Nagafen](/faction/249).l

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

o

r

d

 

N

a

g

a

f

e

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

1

0

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

X

(

)

 

>

 

-

6

5

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

1

5

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

 

>

 

-

1

1

7

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

o

r

d

 

N

a

g

a

f

e

n

 

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

H

a

!

 

 

T

h

e

 

R

i

n

g

 

a

n

d

 

C

l

a

w

s

 

a

r

e

 

d

o

o

m

e

d

!

 

 

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

 

h

a

s

 

b

e

e

n

 

a

w

a

k

e

n

e

d

,

 

w

h

a

t

 

a

 

g

l

o

r

i

o

u

s

 

d

a

y

!

 

 

L

a

d

y

 

V

o

x

,

 

I

 

w

i

l

l

 

s

e

e

 

y

o

u

 

s

o

o

n

,

 

o

u

r

 

l

o

n

g

 

d

e

l

a

y

e

d

 

n

u

p

t

i

a

l

s

 

c

a

n

 

n

o

w

 

p

r

o

c

e

e

d

!

<

/

s

p

a

n

>





