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

 

G

O

D

_

T

Y

P

E

S

 

=

 

{




[

1

6

]

 

=

 

2

2

3

0

0

0

,

 




[

1

7

]

 

=

 

2

2

3

0

0

1

,

 




[

1

8

]

 

=

 

2

2

3

0

0

7

,

 




[

1

9

]

 

=

 

2

2

3

0

0

4

,

 




[

2

0

]

 

=

 

2

2

3

0

0

6

,

 




[

2

1

]

 

=

 

2

2

3

0

0

5

,

 




[

2

2

]

 

=

 

2

2

3

0

0

2

,

 




[

2

3

]

 

=

 

2

2

3

0

0

3

,

 




}

;




l

o

c

a

l

 

T

E

L

E

P

O

R

T

_

L

O

C

S

 

=

 

{




[

1

7

]

 

=

 

{

 

2

1

4

,

 

-

2

1

0

,

 

1

0

,

 

-

3

5

,

 

0

 

}

,

	

	




[

1

8

]

 

=

 

{

 

7

6

,

 

0

,

 

0

,

 

4

,

 

0

 

}

,

	

	

	

	




[

1

9

]

 

=

 

{

 

7

2

,

 

1

0

2

9

,

 

-

7

7

3

,

 

1

0

8

,

 

0

 

}

,

	

	




[

2

0

]

 

=

 

{

 

2

1

4

,

 

-

2

1

0

,

 

1

0

,

 

-

3

5

,

 

0

 

}

,

	

	




[

2

1

]

 

=

 

{

 

2

0

5

,

 

-

1

7

5

0

,

 

-

1

2

4

5

,

 

-

5

9

,

 

0

 

}

,

	




[

2

2

]

 

=

 

{

 

2

0

4

,

 

1

6

6

8

,

 

2

8

2

,

 

2

1

2

,

 

0

 

}

,

	

	




[

2

3

]

 

=

 

{

 

2

0

7

,

 

-

3

4

1

,

 

1

7

0

6

,

 

-

4

9

1

,

 

0

 

}

,

	




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

X

(

)

 

<

 

5

0

0

 

o

r

 

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

 

5

0

0

 

)

 

t

h

e

n







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

,

 

8

,

 

0

,

 

t

o

s

t

r

i

n

g

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

D

(

)

)

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

 

1

7

 

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

 

G

O

D

_

T

Y

P

E

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

7

 

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

G

O

D

_

T

Y

P

E

S

[

1

7

]

)

 

a

n

d

 

n

o

t

 

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

G

O

D

_

T

Y

P

E

S

[

1

6

]

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

u

n

p

a

c

k

(

T

E

L

E

P

O

R

T

_

L

O

C

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

l

s

e




i

f

 

(

 

n

o

t

 

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

G

O

D

_

T

Y

P

E

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

u

n

p

a

c

k

(

T

E

L

E

P

O

R

T

_

L

O

C

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

F

a

i

n

t

 

e

n

e

r

g

y

 

s

w

i

r

l

s

 

s

l

o

w

l

y

 

t

h

r

o

u

g

h

 

t

h

e

 

p

o

r

t

a

l

,

 

b

u

t

 

n

o

t

h

i

n

g

 

h

a

p

p

e

n

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

 

d

o

o

r

_

i

d

 

<

 

5

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

 

6

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

,

 

4

,

 

0

,

 

d

o

o

r

_

i

d

.

.

"

;

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

)

;



















#

#

 

D

i

a

l

o

g




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

m

e

s

s

a

g

e

 

=

=

 

"

s

h

u

t

d

o

w

n

 

i

n

s

t

a

n

c

e

 

n

o

w

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

,

 

9

,

 

0

,

 

"

1

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

 

e

.

m

e

s

s

a

g

e

 

=

=

 

"

s

h

u

t

d

o

w

n

 

i

n

s

t

a

n

c

e

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

,

 

9

,

 

0

,

 

"

2

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

 

e

.

m

e

s

s

a

g

e

:

f

i

n

d

(

"

s

e

t

 

r

a

i

d

 

i

d

 

t

o

 

%

d

+

"

)

 

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

 

_

,

 

_

,

 

i

d

 

=

 

e

.

m

e

s

s

a

g

e

:

f

i

n

d

(

"

s

e

t

 

r

a

i

d

 

i

d

 

t

o

 

(

%

d

+

)

"

)




i

f

 

(

 

i

d

 

)

 

t

h

e

n




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

,

 

9

,

 

0

,

 

"

3

;

"

.

.

i

d

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

m

e

s

s

a

g

e

 

=

=

 

"

s

k

i

p

 

p

h

a

s

e

 

1

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

,

 

9

,

 

0

,

 

"

4

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

 

e

.

m

e

s

s

a

g

e

 

=

=

 

"

z

o

n

e

 

s

t

a

t

u

s

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

,

 

9

,

 

0

,

 

"

5

"

)

;








