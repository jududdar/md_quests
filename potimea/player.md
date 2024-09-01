l

o

c

a

l

 

P

O

T

I

M

E

A

_

C

O

N

T

R

O

L

L

E

R

_

T

Y

P

E

 

=

 

2

1

9

0

5

3

;




l

o

c

a

l

 

P

O

T

I

M

E

B

_

C

O

N

T

R

O

L

L

E

R

_

T

Y

P

E

 

=

 

2

2

3

0

7

7

;




l

o

c

a

l

 

D

I

A

L

S

 

=

 

{

 

2

,

 

4

,

 

1

,

 

5

,

 

3

 

}

;







l

o

c

a

l

 

b

l

o

c

k

s

 

=

 

{

}

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

 

>

=

 

8

 

a

n

d

 

d

o

o

r

_

i

d

 

<

=

 

1

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

 

n

o

w

 

=

 

o

s

.

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

 

c

h

a

r

I

D

 

=

 

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

a

c

t

e

r

I

D

(

)

;




i

f

 

(

 

b

l

o

c

k

s

[

c

h

a

r

I

D

]

 

a

n

d

 

b

l

o

c

k

s

[

c

h

a

r

I

D

]

 

>

 

n

o

w

 

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

 

r

a

i

d

 

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

R

a

i

d

(

)

;







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

G

e

t

G

M

(

)

 

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

L

e

v

e

l

(

)

 

<

 

6

5

 

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

 

a

n

d

 

(

n

o

t

 

r

a

i

d

.

v

a

l

i

d

 

o

r

 

r

a

i

d

:

R

a

i

d

C

o

u

n

t

(

)

 

<

 

7

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

Y

o

u

 

d

o

n

'

t

 

h

a

v

e

 

s

u

f

f

i

c

i

e

n

t

 

p

o

w

e

r

 

t

o

 

a

f

f

e

c

t

 

t

h

i

n

g

s

 

i

n

 

t

h

e

 

P

l

a

n

e

 

o

f

 

T

i

m

e

.

 

G

a

t

h

e

r

 

y

o

u

r

 

f

o

r

c

e

s

 

t

o

 

i

n

c

r

e

a

s

e

 

y

o

u

r

 

s

t

r

e

n

g

t

h

.

"

)

;




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

 

i

n

s

t

a

n

c

e

I

D

 

=

 

0

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

t

i

m

e

_

i

n

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




i

n

s

t

a

n

c

e

I

D

 

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

t

i

m

e

_

i

n

s

t

a

n

c

e

)

 

o

r

 

0

;










d

o

o

r

_

i

d

 

=

 

d

o

o

r

_

i

d

 

-

 

7

;







e

q

.

s

i

g

n

a

l

(

P

O

T

I

M

E

A

_

C

O

N

T

R

O

L

L

E

R

_

T

Y

P

E

,

 

3

,

 

0

,

 

c

h

a

r

I

D

.

.

"

;

"

.

.

D

I

A

L

S

[

d

o

o

r

_

i

d

]

.

.

"

;

"

.

.

r

a

i

d

:

G

e

t

I

D

(

)

.

.

"

;

"

.

.

i

n

s

t

a

n

c

e

I

D

)

;







b

l

o

c

k

s

[

c

h

a

r

I

D

]

 

=

 

n

o

w

 

+

 

2

;





