# Shuttle I

[Shuttle I](/npc/846) is a level 50 Launch Warrior that spawns in [Timorous Deep](/zone/96).





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




i

f

 

(

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

 

~

=

 

-

1

)

 

t

h

e

n




e

q

.

d

e

b

u

g

(

"

W

e

 

a

r

e

 

i

n

 

a

n

 

i

n

s

t

a

n

c

e

 

(

"

 

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

 

.

.

 

"

)

,

 

i

g

n

o

r

i

n

g

 

e

v

e

n

t

_

s

p

a

w

n

 

f

o

r

 

"

 

.

.

 

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

N

a

m

e

(

)

)

;




*

*

S

h

u

t

t

l

e

 

I

 

d

e

s

p

a

w

n

s

.

*

*




e

l

s

e




l

o

c

a

l

 

z

o

n

e

_

t

i

m

e

 

=

 

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

t

i

m

e

(

)

;




l

o

c

a

l

 

h

o

u

r

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

h

o

u

r

"

]

;




l

o

c

a

l

 

m

i

n

u

t

e

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

m

i

n

u

t

e

"

]

;




e

q

.

d

e

b

u

g

(

"

S

h

u

t

t

l

e

 

s

p

a

w

n

e

d

!

 

N

a

m

e

 

i

s

:

 

S

h

u

t

t

l

e

 

I

 

T

i

m

e

 

i

s

:

 

"

 

.

.

 

h

o

u

r

 

.

.

"

:

"

 

.

.

 

m

i

n

u

t

e

 

.

.

 

"

"

,

 

1

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




e

q

.

s

t

a

r

t

(

1

6

)

;



















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




l

o

c

a

l

 

z

o

n

e

_

t

i

m

e

 

=

 

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

t

i

m

e

(

)

;




l

o

c

a

l

 

h

o

u

r

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

h

o

u

r

"

]

;




l

o

c

a

l

 

m

i

n

u

t

e

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

m

i

n

u

t

e

"

]

;




i

f

(

e

.

g

r

i

d

i

d

 

=

=

 

1

6

 

a

n

d

 

e

.

w

p

 

=

=

 

3

)

 

t

h

e

n




e

q

.

s

p

a

w

n

_

c

o

n

d

i

t

i

o

n

(

"

b

u

t

c

h

e

r

"

,

3

,

1

)

;




e

q

.

s

p

a

w

n

_

c

o

n

d

i

t

i

o

n

(

"

t

i

m

o

r

o

u

s

"

,

5

,

0

)

;




e

q

.

d

e

b

u

g

(

"

S

h

u

t

t

l

e

 

t

o

 

b

u

t

c

h

e

r

 

(

4

)

 

h

a

s

 

r

e

a

c

h

e

d

 

i

t

s

 

d

e

s

t

i

n

a

t

i

o

n

!

 

N

a

m

e

 

i

s

:

 

S

h

u

t

t

l

e

 

I

 

T

i

m

e

 

i

s

:

 

"

 

.

.

 

h

o

u

r

 

.

.

"

:

"

 

.

.

 

m

i

n

u

t

e

 

.

.

 

"

"

,

 

1

)

;




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

F

o

r

e

a

c

h

C

l

i

e

n

t

(




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

)




e

n

t

:

S

i

g

n

a

l

(

2

)

;




e

n

d

,




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

)




l

o

c

a

l

 

p

x

 

=

 

e

n

t

:

G

e

t

X

(

)

;




l

o

c

a

l

 

p

y

 

=

 

e

n

t

:

G

e

t

Y

(

)

;




l

o

c

a

l

 

b

o

a

t

_

i

d

 

=

 

e

n

t

:

G

e

t

B

o

a

t

I

D

(

)

;




l

o

c

a

l

 

d

i

f

f

_

b

o

a

t

_

c

h

e

c

k

 

=

 

b

o

a

t

_

i

d

 

=

=

 

8

3

8

 

o

r

 

b

o

a

t

_

i

d

 

=

=

 

8

4

7

 

o

r

 

b

o

a

t

_

i

d

 

=

=

 

8

4

8

 

o

r

 

b

o

a

t

_

i

d

 

=

=

 

8

4

9

 

o

r

 

b

o

a

t

_

i

d

 

=

=

 

9

6

0

7

5

;







l

o

c

a

l

 

v

a

l

i

d

_

p

o

s

_

c

h

e

c

k

 

=

 

p

x

 

>

=

 

-

7

7

2

1

 

a

n

d

 

p

x

 

<

=

 

-

7

5

0

3

 

a

n

d

 

p

y

 

>

=

 

3

4

4

4

 

a

n

d

 

p

y

 

<

=

 

3

7

7

2

;







i

f

(

d

i

f

f

_

b

o

a

t

_

c

h

e

c

k

 

a

n

d

 

v

a

l

i

d

_

p

o

s

_

c

h

e

c

k

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







)

;




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

F

o

r

e

a

c

h

C

l

i

e

n

t

(




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

)




e

n

t

:

M

o

v

e

P

C

(

6

8

,

 

3

5

9

5

,

 

4

9

1

,

 

1

9

,

 

0

)

;




e

n

d

,




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

)




l

o

c

a

l

 

p

x

 

=

 

e

n

t

:

G

e

t

X

(

)

;




l

o

c

a

l

 

p

y

 

=

 

e

n

t

:

G

e

t

Y

(

)

;







l

o

c

a

l

 

v

a

l

i

d

_

p

o

s

_

c

h

e

c

k

 

=

 

p

x

 

>

=

 

-

7

7

2

1

 

a

n

d

 

p

x

 

<

=

 

-

7

5

0

3

 

a

n

d

 

p

y

 

>

=

 

3

4

4

4

 

a

n

d

 

p

y

 

<

=

 

3

7

7

2

;




i

f

(

e

n

t

:

G

e

t

B

o

a

t

I

D

(

)

 

=

=

 

8

4

6

 

a

n

d

 

v

a

l

i

d

_

p

o

s

_

c

h

e

c

k

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







)

;





