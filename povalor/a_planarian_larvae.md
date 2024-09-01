# a planarian larvae

[a planarian larvae](/npc/205053) is a level 52 Worm Warrior that spawns in [Plane of Valor](/zone/208).

Their primary faction is [Inhabitants of Disease](/faction/1654).








l

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




l

o

c

a

l

 

s

p

a

w

n

L

o

c

s

 

=

 

{

}

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




e

q

.

s

e

t

_

t

i

m

e

r

(

"

m

o

v

e

"

,

 

2

4

0

0

0

 

+

 

m

a

t

h

.

r

a

n

d

o

m

(

1

0

0

0

,

 

5

0

0

0

)

)

;




s

p

a

w

n

L

o

c

s

[

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

I

D

(

)

]

 

=

 

{

 

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

,

 

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

,

 

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

 

}
















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

 

 

a

 

p

l

a

n

a

r

i

a

n

 

l

a

r

v

a

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

m

o

v

e

"

)

;




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

b

u

r

r

o

w

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

m

o

v

e

"

)

;




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

b

u

r

r

o

w

"

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

 

e

v

e

n

t

_

d

e

a

t

h

(

e

)




s

p

a

w

n

L

o

c

s

[

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

I

D

(

)

]

 

=

 

n

i

l

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

s

e

l

f

:

C

h

a

r

m

e

d

(

)

 

)

 

t

h

e

n




r

e

t

u

r

n

;










l

o

c

a

l

 

l

 

=

 

s

p

a

w

n

L

o

c

s

[

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

I

D

(

)

]

;







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

m

o

v

e

"

 

)

 

t

h

e

n




i

f

 

(

 

l

.

b

 

=

=

 

1

 

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

M

o

v

e

T

o

(

l

.

b

x

 

+

 

m

a

t

h

.

r

a

n

d

o

m

(

-

1

,

 

1

)

,

 

l

.

b

y

 

+

 

m

a

t

h

.

r

a

n

d

o

m

(

-

1

,

 

1

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

 

-

1

,

 

f

a

l

s

e

)

;

 




e

l

s

e

i

f

 

(

 

m

a

t

h

.

r

a

n

d

o

m

(

1

,

 

5

)

 

=

=

 

1

 

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

m

o

v

e

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

b

u

r

r

o

w

*

 

f

o

r

 

7

 

s

e

c

o

n

d

s




l

.

b

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




l

.

b

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




e

.

s

e

l

f

:

M

o

v

e

T

o

(

l

.

b

x

 

+

 

m

a

t

h

.

r

a

n

d

o

m

(

-

1

,

 

1

)

,

 

l

.

b

y

 

+

 

m

a

t

h

.

r

a

n

d

o

m

(

-

1

,

 

1

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

 

-

1

,

 

f

a

l

s

e

)

;

 




l

.

b

 

=

 

1

;




e

l

s

e




e

.

s

e

l

f

:

M

o

v

e

T

o

(

l

.

x

 

+

 

m

a

t

h

.

r

a

n

d

o

m

(

-

2

0

,

 

2

0

)

,

 

l

.

y

 

+

 

m

a

t

h

.

r

a

n

d

o

m

(

-

2

0

,

 

2

0

)

,

 

l

.

z

,

 

-

1

,

 

t

r

u

e

)

;










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

b

u

r

r

o

w

"

 

)

 

t

h

e

n




i

f

 

(

 

l

.

b

 

=

=

 

1

 

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

m

o

v

e

*




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

b

u

r

r

o

w

*

 

f

o

r

 

4

0

 

s

e

c

o

n

d

s




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

3

0

0

0

,

 

3

0

0

0

,

 

0

,

 

0

,

 

t

r

u

e

,

 

t

r

u

e

)

;

 




l

.

b

 

=

 

2

;




e

l

s

e

i

f

 

(

 

l

.

b

 

=

=

 

2

 

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

l

.

x

,

 

l

.

y

,

 

l

.

z

,

 

m

a

t

h

.

r

a

n

d

o

m

(

0

,

 

2

5

5

)

,

 

t

r

u

e

,

 

t

r

u

e

)

;

 




e

q

.

s

e

t

_

t

i

m

e

r

(

"

m

o

v

e

"

,

 

2

4

0

0

0

 

+

 

m

a

t

h

.

r

a

n

d

o

m

(

1

0

0

0

,

 

5

0

0

0

)

)

;




l

.

b

 

=

 

n

i

l

;








