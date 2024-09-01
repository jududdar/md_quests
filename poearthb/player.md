l

o

c

a

l

 

D

O

O

R

1

_

I

D

S

 

=

 

{

 

3

6

9

4

5

3

,

 

3

6

9

4

5

4

,

 

3

6

9

4

5

5

,

 

3

6

9

4

5

6

,

 

3

6

9

4

6

9

,

 

3

6

9

4

7

0

,

 

3

6

9

4

7

4

,

 

3

6

9

4

7

5

,

 

3

6

9

4

7

6

,

 

3

6

9

4

7

9

,




3

6

9

4

5

8

,

 

3

6

9

4

5

9

,

 

3

6

9

4

8

0

,

 

3

6

9

4

8

1

,

 

3

6

9

4

6

8

,

 

3

6

9

4

7

1

,

 

3

6

9

4

7

2

,

 

3

6

9

4

7

3

,

	

3

6

9

4

6

4

,

 

3

6

9

4

6

5

,




3

6

9

4

7

7

,

 

3

6

9

4

7

8

,

 

3

6

9

4

5

7

,

 

3

6

9

4

6

0

,

 

3

6

9

4

6

1

,

 

3

6

9

4

6

2

,

 

3

6

9

4

6

3

,

 

3

6

9

4

6

6

,

 

3

6

9

4

6

7

 

}

;







l

o

c

a

l

 

D

O

O

R

2

_

I

D

S

 

=

 

{

 

3

6

9

4

2

6

,

 

3

6

9

4

2

7

,

 

3

6

9

4

5

1

,

 

3

6

9

4

5

2

,

 

3

6

9

4

3

0

,

 

3

6

9

4

3

3

,

 

3

6

9

4

2

9

,

 

3

6

9

4

3

1

,

 

3

6

9

4

3

6

,

 

3

6

9

4

5

0

,




3

6

9

4

2

8

,

 

3

6

9

4

3

2

,

 

3

6

9

4

3

4

,

 

3

6

9

4

3

8

,

 

3

6

9

4

3

9

,

 

3

6

9

4

4

0

,

 

3

6

9

4

4

1

,

 

3

6

9

4

4

6

,

 

3

6

9

4

4

7

,

 

3

6

9

4

4

8

,




3

6

9

4

4

9

,

 

3

6

9

4

4

2

,

 

3

6

9

4

4

3

,

 

3

6

9

4

4

4

,

 

3

6

9

4

4

5

 

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

 

=

=

 

2

 

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

 

e

l

i

s

t

 

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

;







f

o

r

 

_

,

 

i

d

 

i

n

 

i

p

a

i

r

s

(

D

O

O

R

1

_

I

D

S

)

 

d

o




i

f

 

(

 

e

l

i

s

t

:

G

e

t

S

p

a

w

n

B

y

I

D

(

i

d

)

:

G

e

t

N

P

C

(

)

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

A

s

 

y

o

u

 

a

t

t

e

m

p

t

 

t

o

 

m

o

v

e

 

t

h

e

 

w

a

l

l

 

o

f

 

s

t

o

n

e

 

i

t

 

i

s

 

c

l

e

a

r

 

t

h

a

t

 

i

t

 

i

s

 

b

e

i

n

g

 

h

e

l

d

 

i

n

 

p

l

a

c

e

 

b

y

 

a

 

p

o

w

e

r

f

u

l

 

f

o

r

c

e

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

3

)

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

 

4

 

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

 

e

l

i

s

t

 

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

;




l

o

c

a

l

 

s

h

u

t

 

=

 

f

a

l

s

e

;







f

o

r

 

_

,

 

i

d

 

i

n

 

i

p

a

i

r

s

(

D

O

O

R

2

_

I

D

S

)

 

d

o




i

f

 

(

 

e

l

i

s

t

:

G

e

t

S

p

a

w

n

B

y

I

D

(

i

d

)

:

G

e

t

N

P

C

(

)

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




s

h

u

t

 

=

 

t

r

u

e

;




b

r

e

a

k

;













i

f

 

(

 

n

o

t

 

s

h

u

t

 

a

n

d

 

(

e

l

i

s

t

:

I

s

M

o

b

S

p

a

w

n

e

d

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

2

2

0

3

5

)

 

o

r

 

e

l

i

s

t

:

I

s

M

o

b

S

p

a

w

n

e

d

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

2

2

0

3

6

)

 

o

r




e

l

i

s

t

:

I

s

M

o

b

S

p

a

w

n

e

d

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

2

2

0

3

7

)

 

o

r

 

e

l

i

s

t

:

I

s

M

o

b

S

p

a

w

n

e

d

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

2

2

0

3

8

)

)




)

 

t

h

e

n




s

h

u

t

 

=

 

t

r

u

e

;










i

f

 

(

 

s

h

u

t

 

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

 

m

a

s

s

i

v

e

 

w

a

l

l

 

o

f

 

r

o

c

k

,

 

d

i

r

t

 

a

n

d

 

s

t

o

n

e

 

s

e

e

m

s

 

t

o

 

b

e

 

i

m

p

e

n

e

t

r

a

b

l

e

.

 

 

I

t

 

i

s

 

o

b

v

i

o

u

s

l

y

 

h

e

l

d

 

i

n

 

p

l

a

c

e

 

b

y

 

a

 

m

a

g

i

c

a

l

 

f

o

r

c

e

.

"

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

4

)

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

5

)

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





