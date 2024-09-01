l

o

c

a

l

 

l

e

v

e

l

_

f

o

r

_

t

i

e

r

_

t

w

o

 

=

 

5

5

;

	

	

	




l

o

c

a

l

 

l

e

v

e

l

_

f

o

r

_

t

i

e

r

_

t

h

r

e

e

 

=

 

6

2

;




l

o

c

a

l

 

l

e

v

e

l

_

f

o

r

_

t

i

e

r

_

f

o

u

r

 

=

 

2

5

5

;




l

o

c

a

l

 

l

e

v

e

l

_

f

o

r

_

e

l

e

m

e

n

t

a

l

 

=

 

2

5

5

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

 

1

6

 

o

r

 

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

1

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

L

e

v

e

l

(

)

 

>

=

 

l

e

v

e

l

_

f

o

r

_

t

i

e

r

_

t

w

o

 

o

r

 

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

m

a

v

u

i

n

 

a

n

d

 

q

g

l

o

b

a

l

s

.

m

a

v

u

i

n

 

=

=

 

"

3

"

)

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

0

)

 

=

=

 

f

a

l

s

e

 

o

r

 

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

0

8

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

0

8

)

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

e

s

s

a

g

e

(

1

3

,

 

"

Y

o

u

 

l

a

c

k

 

t

h

e

 

w

i

l

l

 

t

o

 

p

a

s

s

 

t

h

r

o

u

g

h

 

t

h

i

s

 

p

o

r

t

a

l

 

s

a

f

e

l

y

.

"

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

 

1

2

)

 

t

h

e

n







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

H

a

s

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

0

0

)

 

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

I

t

e

m

I

D

A

t

(

0

)

 

=

=

 

9

2

9

4

 

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

9

2

9

4

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

9

2

9

4

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

G

e

t

L

e

v

e

l

(

)

 

>

=

 

l

e

v

e

l

_

f

o

r

_

t

i

e

r

_

t

w

o

 

o

r

 

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

9

2

9

4

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

0

0

)

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

e

s

s

a

g

e

(

1

3

,

 

"

Y

o

u

 

l

a

c

k

 

t

h

e

 

w

i

l

l

 

t

o

 

p

a

s

s

 

t

h

r

o

u

g

h

 

t

h

i

s

 

p

o

r

t

a

l

 

s

a

f

e

l

y

.

"

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

 

9

3

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

I

t

e

m

I

D

A

t

(

0

)

 

=

=

 

2

9

2

1

3

 

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

9

2

1

3

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

9

2

1

3

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

G

e

t

L

e

v

e

l

(

)

 

>

=

 

l

e

v

e

l

_

f

o

r

_

t

i

e

r

_

t

w

o

 

o

r

 

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

f

u

i

r

s

t

e

l

 

a

n

d

 

q

g

l

o

b

a

l

s

.

f

u

i

r

s

t

e

l

 

=

=

 

"

5

"

 

a

n

d

 

q

g

l

o

b

a

l

s

.

t

h

e

l

i

n

 

a

n

d

 

q

g

l

o

b

a

l

s

.

t

h

e

l

i

n

 

=

=

 

"

4

"

)

 

o

r

 

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

9

2

1

3

)

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

0

7

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

0

7

)

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

e

s

s

a

g

e

(

1

3

,

 

"

Y

o

u

 

l

a

c

k

 

t

h

e

 

w

i

l

l

 

t

o

 

p

a

s

s

 

t

h

r

o

u

g

h

 

t

h

i

s

 

p

o

r

t

a

l

 

s

a

f

e

l

y

.

"

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

 

4

8

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

 

k

a

r

a

n

a

 

=

 

t

o

n

u

m

b

e

r

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

k

a

r

a

n

a

 

o

r

 

0

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

G

e

t

L

e

v

e

l

(

)

 

>

=

 

l

e

v

e

l

_

f

o

r

_

t

i

e

r

_

t

h

r

e

e

 

o

r

 

k

a

r

a

n

a

 

>

=

 

3

 

o

r

 

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

0

9

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

0

9

)

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

e

s

s

a

g

e

(

1

3

,

 

"

Y

o

u

 

l

a

c

k

 

t

h

e

 

w

i

l

l

 

t

o

 

p

a

s

s

 

t

h

r

o

u

g

h

 

t

h

i

s

 

p

o

r

t

a

l

 

s

a

f

e

l

y

.

"

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

3

)

 

t

h

e

n







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

H

a

s

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

1

)

 

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

I

t

e

m

I

D

A

t

(

0

)

 

=

=

 

2

9

2

1

4

 

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

9

2

1

4

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

9

2

1

4

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

G

e

t

L

e

v

e

l

(

)

 

>

=

 

l

e

v

e

l

_

f

o

r

_

t

i

e

r

_

t

h

r

e

e

 

o

r

 

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

9

2

1

4

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

1

)

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

e

s

s

a

g

e

(

1

3

,

 

"

Y

o

u

 

l

a

c

k

 

t

h

e

 

w

i

l

l

 

t

o

 

p

a

s

s

 

t

h

r

o

u

g

h

 

t

h

i

s

 

p

o

r

t

a

l

 

s

a

f

e

l

y

.

"

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

4

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

 

z

e

k

s

 

=

 

t

o

n

u

m

b

e

r

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

k

s

 

o

r

 

0

)

;




i

f

 

(

 

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

I

t

e

m

I

D

A

t

(

0

)

 

=

=

 

2

9

2

1

5

 

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

9

2

1

5

)

 

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

9

2

1

5

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

G

e

t

L

e

v

e

l

(

)

 

>

=

 

6

0

 

o

r

 

z

e

k

s

 

>

=

 

2

 

o

r

 

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

9

2

1

5

)

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

4

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

4

)

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

e

s

s

a

g

e

(

1

3

,

 

"

Y

o

u

 

l

a

c

k

 

t

h

e

 

w

i

l

l

 

t

o

 

p

a

s

s

 

t

h

r

o

u

g

h

 

t

h

i

s

 

p

o

r

t

a

l

 

s

a

f

e

l

y

.

"

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

 

z

e

k

s

 

=

 

t

o

n

u

m

b

e

r

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

k

s

 

o

r

 

0

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

G

e

t

L

e

v

e

l

(

)

 

>

=

 

l

e

v

e

l

_

f

o

r

_

t

i

e

r

_

f

o

u

r

 

o

r

 

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

c

i

p

h

e

r

 

a

n

d

 

z

e

k

s

 

>

=

 

6

)

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

2

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

2

)

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

e

s

s

a

g

e

(

1

3

,

 

"

Y

o

u

 

l

a

c

k

 

t

h

e

 

w

i

l

l

 

t

o

 

p

a

s

s

 

t

h

r

o

u

g

h

 

t

h

i

s

 

p

o

r

t

a

l

 

s

a

f

e

l

y

.

"

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

 

8

2

)

 

t

h

e

n







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

H

a

s

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

7

)

 

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

L

e

v

e

l

(

)

 

>

=

 

l

e

v

e

l

_

f

o

r

_

e

l

e

m

e

n

t

a

l

 

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

7

)

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

e

s

s

a

g

e

(

1

3

,

 

"

Y

o

u

 

l

a

c

k

 

t

h

e

 

w

i

l

l

 

t

o

 

p

a

s

s

 

t

h

r

o

u

g

h

 

t

h

i

s

 

p

o

r

t

a

l

 

s

a

f

e

l

y

.

"

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

 

8

1

 

o

r

 

d

o

o

r

_

i

d

 

=

=

 

8

3

 

o

r

 

d

o

o

r

_

i

d

 

=

=

 

8

4

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

L

e

v

e

l

(

)

 

>

=

 

l

e

v

e

l

_

f

o

r

_

e

l

e

m

e

n

t

a

l

 

o

r

 

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

 

a

n

d

 

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

)

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

6

)

 

=

=

 

f

a

l

s

e

 

o

r

 

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

5

)

 

=

=

 

f

a

l

s

e

 

o

r

 

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

8

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

6

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

5

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

8

)

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

e

s

s

a

g

e

(

1

3

,

 

"

Y

o

u

 

l

a

c

k

 

t

h

e

 

w

i

l

l

 

t

o

 

p

a

s

s

 

t

h

r

o

u

g

h

 

t

h

i

s

 

p

o

r

t

a

l

 

s

a

f

e

l

y

.

"

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

 

1

8

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

G

M

(

)

 

o

r

 

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

L

e

v

e

l

(

)

 

>

=

 

6

5

 

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

 

a

n

d

 

q

g

l

o

b

a

l

s

.

t

i

m

e

 

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

M

e

s

s

a

g

e

(

0

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

e

s

s

a

g

e

(

1

3

,

 

"

Y

o

u

 

l

a

c

k

 

t

h

e

 

w

i

l

l

 

t

o

 

p

a

s

s

 

t

h

r

o

u

g

h

 

t

h

i

s

 

p

o

r

t

a

l

 

s

a

f

e

l

y

.

"

)

;








