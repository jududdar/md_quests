# Shuttle II

[Shuttle II](/npc/847) is a level 50 Launch Warrior that spawns in [Butcherblock Mountains](/zone/68).





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

B

o

a

t

 

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

s

t

a

r

t

(

2

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

7

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

 

2

1

 

a

n

d

 

e

.

w

p

 

=

=

 

1

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

(

)

;




e

q

.

m

o

v

e

_

t

o

(

3

1

5

8

,

 

8

3

4

,

 

-

1

3

,

 

6

5

.

2

7

,

 

t

r

u

e

)

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

7

 

a

n

d

 

e

.

w

p

 

=

=

 

1

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

4

,

0

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

6

,

1

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

 

t

i

m

o

r

o

u

s

 

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

4

6

 

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

 

3

5

6

7

 

a

n

d

 

p

x

 

<

=

 

3

6

5

5

 

a

n

d

 

p

y

 

>

=

 

4

4

0

 

a

n

d

 

p

y

 

<

=

 

4

6

4

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

9

6

,

 

-

7

5

8

0

,

 

3

5

8

0

,

 

1

9

,

 

1

4

4

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

 

3

5

6

7

 

a

n

d

 

p

x

 

<

=

 

3

6

5

5

 

a

n

d

 

p

y

 

>

=

 

4

4

0

 

a

n

d

 

p

y

 

<

=

 

4

6

4

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

7

 

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





