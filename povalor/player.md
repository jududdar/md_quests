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




l

o

c

a

l

 

a

d

U

p

 

=

 

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

\

#

A

e

r

i

n

\

`

D

a

r

]

(

/

n

p

c

/

2

0

8

0

7

4

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

 

3

 

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

a

e

r

i

n

d

a

r

 

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

a

e

r

i

n

d

a

r

 

=

=

 

"

2

"

 

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










i

f

 

(

 

n

o

t

 

q

g

l

o

b

a

l

s

.

a

e

r

i

n

d

a

r

 

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




e

l

s

e




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

a

e

r

i

n

d

a

r

"

,

 

"

2

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

c

l

_

a

e

r

i

n

d

a

r

 

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

l

e

t

e

_

g

l

o

b

a

l

(

"

c

l

_

a

e

r

i

n

d

a

r

"

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

1

)

;
















e

l

s

e

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

 

6

 

a

n

d

 

a

d

U

p

 

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

8

,

 

3

5

2

,

 

2

1

7

2

,

 

3

3

,

 

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

P

e

t

(

)

.

v

a

l

i

d

 

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

G

e

t

P

e

t

(

)

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

P

e

t

(

)

:

G

M

M

o

v

e

(

3

5

2

,

 

2

1

7

2

,

 

3

3

,

 

0

)

;













e

l

s

e

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

 

9

 

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

5

5

9

6

 

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

 

d

o

o

r

 

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

D

o

o

r

s

B

y

D

o

o

r

I

D

(

2

)

;




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

1

 

a

n

d

 

n

o

t

 

a

d

U

p

 

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





