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

 

>

=

 

1

4

 

a

n

d

 

i

d

 

<

=

 

1

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

1

4

3

1

1

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

1

4

3

1

2

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

1

4

3

1

3

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

1

4

3

2

0

)

	




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

 

2

 

o

r

 

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

	







i

f

 

(

 

n

o

t

 

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

V

a

l

l

o

n

 

Z

e

k

]

(

/

n

p

c

/

2

1

4

3

1

6

)




a

n

d

 

n

o

t

 

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

V

a

l

l

o

n

 

Z

e

k

]

(

/

n

p

c

/

2

1

4

3

1

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

o

v

e

P

C

(

2

1

4

,

 

2

7

9

,

 

1

8

2

,

 

5

,

 

1

2

8

*

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

2

7

9

,

 

1

8

2

,

 

5

,

 

1

2

8

*

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

0

,

 

"

T

h

e

 

d

o

o

r

s

 

a

r

e

 

h

e

l

d

 

s

h

u

t

 

b

y

 

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

s

.

"

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

 

4

 

o

r

 

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

	







i

f

 

(

 

n

o

t

 

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

T

a

l

l

o

n

 

Z

e

k

]

(

/

n

p

c

/

2

1

4

0

2

6

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

o

v

e

P

C

(

2

1

4

,

 

2

7

9

,

 

1

8

2

,

 

5

,

 

1

2

8

*

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

2

7

9

,

 

1

8

2

,

 

5

,

 

1

2

8

*

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

0

,

 

"

T

h

e

 

d

o

o

r

s

 

a

r

e

 

h

e

l

d

 

s

h

u

t

 

b

y

 

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

s

.

"

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

 

r

z

 

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

1

4

3

1

2

)

;

	




i

f

 

(

 

r

z

 

a

n

d

 

r

z

.

v

a

l

i

d

 

a

n

d

 

r

z

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

4

,

 

r

z

:

G

e

t

X

(

)

,

 

r

z

:

G

e

t

Y

(

)

,

 

r

z

:

G

e

t

Z

(

)

,

 

r

z

:

G

e

t

H

e

a

d

i

n

g

(

)

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

3

,

 

-

4

,

 

-

1

9

1

,

 

-

6

2

8

,

 

1

4

9

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

 

2

5

 

a

n

d

 

n

o

t

 

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

G

l

y

k

u

s

 

H

e

l

m

i

r

]

(

/

n

p

c

/

2

1

4

0

5

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

M

o

v

e

P

C

(

2

0

3

,

 

-

4

,

 

-

1

9

1

,

 

-

6

2

8

,

 

1

4

9

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

 

2

6

 

a

n

d

 

n

o

t

 

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

T

a

g

r

i

n

 

M

a

l

d

r

i

c

]

(

/

n

p

c

/

2

1

4

0

5

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

M

o

v

e

P

C

(

2

0

3

,

 

-

4

,

 

-

1

9

1

,

 

-

6

2

8

,

 

1

4

9

)

;

	





