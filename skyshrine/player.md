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

 

d

o

o

r

_

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

d

o

o

r

_

i

d

 

=

=

 

2

2

5

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

H

a

s

I

t

e

m

(

2

8

6

0

2

)

 

a

n

d

 

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

K

e

y

R

i

n

g

C

h

e

c

k

(

2

8

6

0

2

)

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

K

e

y

R

i

n

g

A

d

d

(

2

8

6

0

2

)

;







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

K

e

y

R

i

n

g

C

h

e

c

k

(

2

8

6

0

2

)

 

)

 

t

h

e

n




M

o

v

e

G

r

o

u

p

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

G

r

o

u

p

(

)

,

e

.

s

e

l

f

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

X

(

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

Y

(

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

 

7

5

,

 

8

9

4

,

 

-

9

4

2

,

 

3

1

5

,

 

5

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

 

M

o

v

e

G

r

o

u

p

(

f

r

o

z

e

n

_

g

r

o

u

p

,

 

p

l

a

y

e

r

,

 

s

r

c

_

x

,

 

s

r

c

_

y

,

 

s

r

c

_

z

,

 

d

i

s

t

a

n

c

e

,

 

t

g

t

_

x

,

 

t

g

t

_

y

,

 

t

g

t

_

z

,

 

t

g

t

_

h

)




i

f

 

(

 

f

r

o

z

e

n

_

g

r

o

u

p

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




l

o

c

a

l

 

f

r

o

z

e

n

_

c

o

u

n

t

 

=

 

f

r

o

z

e

n

_

g

r

o

u

p

:

G

r

o

u

p

C

o

u

n

t

(

)

;







f

o

r

 

i

 

=

 

0

,

 

f

r

o

z

e

n

_

c

o

u

n

t

 

-

 

1

,

 

1

 

d

o




l

o

c

a

l

 

c

l

i

e

n

t

_

v

 

=

 

f

r

o

z

e

n

_

g

r

o

u

p

:

G

e

t

M

e

m

b

e

r

(

i

)

:

C

a

s

t

T

o

C

l

i

e

n

t

(

)

;







i

f

 

(

c

l

i

e

n

t

_

v

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







i

f

 

(

c

l

i

e

n

t

_

v

:

C

a

l

c

u

l

a

t

e

D

i

s

t

a

n

c

e

(

s

r

c

_

x

,

 

s

r

c

_

y

,

 

s

r

c

_

z

)

 

<

=

 

d

i

s

t

a

n

c

e

)

 

t

h

e

n







c

l

i

e

n

t

_

v

:

M

o

v

e

P

C

(

1

1

7

,

 

t

g

t

_

x

,

 

t

g

t

_

y

,

 

t

g

t

_

z

,

 

t

g

t

_

h

)

;













e

l

s

e




p

l

a

y

e

r

:

M

o

v

e

P

C

(

1

1

7

,

 

t

g

t

_

x

,

 

t

g

t

_

y

,

 

t

g

t

_

z

,

 

t

g

t

_

h

)

;





