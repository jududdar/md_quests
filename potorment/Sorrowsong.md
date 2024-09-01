# Sorrowsong

[Sorrowsong](/npc/207052) is a level 66 Blood Raven Warrior that spawns in [Torment, the Plane of Pain](/zone/207).

Their primary faction is [Servants of Saryrn](/faction/1624).l

o

c

a

l

 

l

o

c

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




l

o

c

 

=

 

1

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

 

1

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

o

r

r

o

w

s

o

n

g

 

c

a

s

t

s

:

*

*

 

[

S

o

r

r

o

w

 

S

o

n

g

]

(

/

s

p

e

l

l

/

3

0

1

1

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

s

o

n

g

*

 

f

o

r

 

5

 

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

p

e

c

i

a

l

A

b

i

l

i

t

y

(

2

4

,

 

0

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

p

e

c

i

a

l

A

b

i

l

i

t

y

(

2

5

,

 

0

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

p

e

c

i

a

l

A

b

i

l

i

t

y

(

3

5

,

 

0

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

B

o

d

y

T

y

p

e

(

2

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

o

c

a

l

 

b

o

s

s

 

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

2

0

7

0

0

1

)

;

 




i

f

 

(

 

b

o

s

s

 

a

n

d

 

b

o

s

s

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

M

o

v

e

T

o

(

b

o

s

s

:

G

e

t

X

(

)

,

 

b

o

s

s

:

G

e

t

Y

(

)

,

 

b

o

s

s

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

s

i

g

n

a

l

 

=

=

 

3

 

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

m

o

v

e

*




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

p

e

c

i

a

l

A

b

i

l

i

t

y

(

2

4

,

 

1

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

p

e

c

i

a

l

A

b

i

l

i

t

y

(

2

5

,

 

1

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

p

e

c

i

a

l

A

b

i

l

i

t

y

(

3

5

,

 

1

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

B

o

d

y

T

y

p

e

(

1

1

,

 

f

a

l

s

e

)

;

	




*

*

S

o

r

r

o

w

s

o

n

g

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

M

o

v

e

T

o

(

1

,

 

-

1

,

 

5

8

0

,

 

1

2

8

,

 

t

r

u

e

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

o

c

 

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

-

6

2

,

 

-

1

3

4

,

 

5

8

0

,

 

0

,

 

t

r

u

e

)

;




l

o

c

 

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

o

c

 

=

=

 

2

 

)

 

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

m

o

v

e

*

 

f

o

r

 

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

6

4

,

 

-

1

6

7

,

 

5

8

0

,

 

0

,

 

t

r

u

e

)

;




l

o

c

 

=

 

3

;




e

l

s

e




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

 

2

5

 

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

M

o

v

e

T

o

(

1

,

 

-

1

,

 

5

8

0

,

 

1

2

8

,

 

t

r

u

e

)

;




l

o

c

 

=

 

1

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

s

o

n

g

"

 

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

o

r

r

o

w

s

o

n

g

 

c

a

s

t

s

:

*

*

 

[

S

o

r

r

o

w

 

S

o

n

g

]

(

/

s

p

e

l

l

/

3

0

1

1

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



















#

#

 

A

r

r

i

v

e

 

a

t

 

W

a

y

p

o

i

n

t

 

S

c

r

i

p

t




i

f

 

(

 

n

o

t

 

e

.

s

e

l

f

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




*

*

S

o

r

r

o

w

s

o

n

g

 

c

a

s

t

s

:

*

*

 

[

S

o

r

r

o

w

 

S

o

n

g

]

(

/

s

p

e

l

l

/

3

0

1

1

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

s

o

n

g

*

 

f

o

r

 

5

 

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

 

(

 

n

o

t

 

e

.

j

o

i

n

e

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

M

o

v

e

T

o

(

1

,

 

-

1

,

 

5

8

0

,

 

1

2

8

,

 

t

r

u

e

)

;





