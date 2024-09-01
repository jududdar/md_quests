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

e

n

t

e

r

_

z

o

n

e

(

e

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

G

e

t

Y

(

)

 

<

 

-

5

0

0

 

a

n

d

 

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

0

0

0

 

a

n

d

 

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

5

0

 

a

n

d

 

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

5

0

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

M

o

v

e

P

C

(

2

0

6

,

 

2

7

0

,

 

5

1

8

,

 

-

4

8

,

 

9

0

*

2

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

c

l

i

c

k

_

d

o

o

r

(

e

)




l

o

c

a

l

 

i

d

 

=

 

e

.

d

o

o

r

:

G

e

t

D

o

o

r

I

D

(

)

;







i

f

 

(

 

i

d

 

=

=

 

7

 

)

 

t

h

e

n




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

e

.

s

e

l

f

)

;




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

.

p

o

i

_

d

o

o

r

 

)

 

t

h

e

n




e

.

d

o

o

r

:

F

o

r

c

e

O

p

e

n

(

e

.

s

e

l

f

)

;










e

l

s

e

i

f

 

(

 

i

d

 

=

=

 

1

4

5

 

)

 

t

h

e

n




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

e

.

s

e

l

f

)

;




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

.

z

e

b

u

x

o

r

u

k

 

=

=

 

"

2

"

 

a

n

d

 

e

.

s

e

l

f

:

H

a

s

I

t

e

m

(

2

9

1

6

5

)

 

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

"

t

i

m

e

"

,

 

"

1

"

,

 

5

,

 

"

F

"

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

Z

o

n

e

F

l

a

g

(

2

1

9

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

Z

o

n

e

F

l

a

g

(

2

2

3

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

e

s

s

a

g

e

(

1

5

,

 

"

Y

o

u

 

h

a

v

e

 

r

e

c

e

i

v

e

d

 

a

 

c

h

a

r

a

c

t

e

r

 

f

l

a

g

!

"

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

e

s

s

a

g

e

(

2

5

7

,

 

"

T

h

e

 

a

g

e

s

 

b

e

g

i

n

 

t

o

 

t

e

a

r

 

t

h

r

o

u

g

h

 

y

o

u

r

 

b

o

d

y

.

 

 

Y

o

u

 

w

a

k

e

 

t

o

 

f

i

n

d

 

y

o

u

r

s

e

l

f

 

i

n

 

a

n

o

t

h

e

r

 

t

i

m

e

.

"

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

P

C

(

2

1

9

,

 

2

2

3

,

 

1

4

0

,

 

1

1

,

 

9

4

)

;








