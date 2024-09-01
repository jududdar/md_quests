# Key Master

[Key Master](/npc/71056) is a level 55 Dwarf Shopkeeper that spawns in [Plane of Sky (Instanced)](/zone/1071).

Their primary faction is [Inhabitants of Sky](/faction/424).





#

#

 

S

i

g

n

a

l

s




l

o

c

a

l

 

q

g

l

o

b

a

l

s

 

=

 

e

q

.

g

e

t

_

q

g

l

o

b

a

l

s

(

)

;




l

o

c

a

l

 

k

e

e

p

e

r

N

a

m

e

 

=

 

"

k

e

e

p

e

r

"

;




k

e

e

p

e

r

N

a

m

e

 

=

 

k

e

e

p

e

r

N

a

m

e

 

.

.

 

e

q

.

g

e

t

_

z

o

n

e

_

g

u

i

l

d

_

i

d

(

)

;




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

 




i

f

(

*

*

s

p

a

w

n

e

d

 

N

P

C

:

*

*

 

 

[

a

n

 

a

z

a

r

a

c

k

]

(

/

n

p

c

/

7

1

1

1

1

)

 

=

=

 

f

a

l

s

e

 

a

n

d

 

*

*

s

p

a

w

n

e

d

 

N

P

C

:

*

*

 

 

[

a

n

 

a

z

a

r

a

c

k

]

(

/

n

p

c

/

7

1

0

3

1

)

 

=

=

 

f

a

l

s

e

)

 

t

h

e

n




*

*

S

p

a

w

n

 

N

P

C

:

*

*

 

 

[

P

r

o

t

e

c

t

o

r

 

o

f

 

S

k

y

]

(

/

n

p

c

/

7

1

5

5

9

)

 

a

t

 

(

*

*

y

:

*

*

 

-

2

5

4

.

4

,

 

*

*

x

:

*

*

 

-

6

0

2

.

2

)










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

 

2

)

 

t

h

e

n




i

f

(

q

g

l

o

b

a

l

s

[

k

e

e

p

e

r

N

a

m

e

]

 

=

=

 

n

i

l

)

 

t

h

e

n







e

q

.

s

e

t

_

g

l

o

b

a

l

(

k

e

e

p

e

r

N

a

m

e

,

"

1

"

,

3

,

"

H

1

"

)

;




*

*

S

p

a

w

n

 

N

P

C

:

*

*

 

 

[

K

e

e

p

e

r

 

o

f

 

S

o

u

l

s

]

(

/

n

p

c

/

7

1

5

7

5

)

 

a

t

 

(

*

*

y

:

*

*

 

7

2

0

,

 

*

*

x

:

*

*

 

-

1

4

8

4

)




























#

#

 

D

i

a

l

o

g




*

*

Y

o

u

 

s

a

y

:

*

*

 

`

h

a

i

l

`







>

*

*

K

e

y

 

M

a

s

t

e

r

 

s

a

y

s

:

*

*

 

H

e

l

l

o

 

t

h

e

r

e

,

 

b

r

a

v

e

 

t

r

a

v

e

l

l

e

r

.

 

I

 

s

e

l

l

 

k

e

y

s

 

t

h

a

t

 

t

a

k

e

 

y

o

u

 

t

o

 

o

t

h

e

r

 

i

s

l

a

n

d

s

 

i

n

 

t

h

i

s

 

h

e

r

e

 

P

l

a

n

e

 

o

f

 

S

k

y

.

 

M

y

 

p

r

i

c

e

s

 

a

r

e

 

t

h

e

 

b

e

s

t

 

a

r

o

u

n

d

.

 

H

e

h

,

 

h

e

h

.




*

*

Y

o

u

 

s

a

y

:

*

*

 

`

w

h

a

t

.

*

 

k

e

y

`







>

*

*

K

e

y

 

M

a

s

t

e

r

 

s

a

y

s

:

*

*

 

T

h

e

 

k

e

y

s

?

 

H

e

h

,

 

h

e

h

.

.

.

 

W

e

l

l

,

 

l

e

t

'

s

 

j

u

s

t

 

s

a

y

 

b

e

t

w

e

e

n

 

y

o

u

 

a

n

d

 

m

e

,

 

t

h

e

m

 

t

h

e

r

e

 

f

a

e

r

i

e

s

 

a

i

n

'

t

 

m

u

c

h

 

o

f

 

t

h

e

 

f

i

g

h

t

i

n

'

 

t

y

p

e

.

 

A

t

 

l

e

a

s

t

 

t

h

e

y

 

a

i

n

'

t

 

a

s

 

s

t

r

o

n

g

 

a

s

 

l

o

t

s

a

 

o

t

h

e

r

 

s

t

u

f

f

 

t

h

a

t

'

s

 

u

p

 

o

n

 

t

h

e

s

e

 

h

e

r

e

 

i

s

l

a

n

d

s

 

t

h

a

t

 

w

e

 

b

e

 

s

t

a

n

d

i

n

'

 

o

n

 

n

o

w

.



















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

s

o

u

l

"

)

 

t

h

e

n




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

s

o

u

l

*











