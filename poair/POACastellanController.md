l

o

c

a

l

 

C

A

S

T

E

L

L

A

N

_

T

Y

P

E

 

=

 

2

1

5

0

0

0

;

 




l

o

c

a

l

 

A

L

R

A

N

D

E

R

I

S

A

N

_

T

Y

P

E

 

=

 

2

1

5

3

8

3

;

 




l

o

c

a

l

 

B

E

L

E

C

O

H

E

N

_

T

Y

P

E

 

=

 

2

1

5

3

8

4

;

 




l

o

c

a

l

 

F

E

R

A

B

A

L

E

N

_

T

Y

P

E

 

=

 

2

1

5

3

8

5

;

 




l

o

c

a

l

 

C

H

A

M

B

E

R

L

A

I

N

_

T

Y

P

E

 

=

 

2

1

5

4

1

1

;

 




l

o

c

a

l

 

A

P

P

R

E

N

T

I

C

E

_

T

Y

P

E

 

=

 

2

1

5

4

1

0

;

 




l

o

c

a

l

 

A

R

M

O

R

_

G

U

Y

_

T

Y

P

E

 

=

 

2

1

5

4

1

8

;

 







l

o

c

a

l

 

C

A

S

T

E

L

L

A

N

_

S

P

A

W

N

I

D

S

 

=

 

{

 

3

6

5

3

3

3

,

 

3

6

5

4

4

4

,

 

3

6

5

6

2

9

,

 

3

6

5

6

7

9

,

 

3

6

5

8

3

3

,

 

3

6

6

0

9

3

,

 

3

6

6

3

1

5

,

 

3

6

6

3

6

9

,

 

3

6

6

4

1

4

,

 

3

6

6

6

1

2

,




3

6

6

7

0

7

,

 

3

6

6

7

9

8

,

 

3

6

7

0

7

9

,

 

3

6

7

0

9

9

,

 

3

6

7

2

8

4

 

}

;




l

o

c

a

l

 

L

O

C

S

 

=

 

{




[

A

L

R

A

N

D

E

R

I

S

A

N

_

T

Y

P

E

]

 

=

 

{

 

4

0

3

,

 

4

6

3

,

 

-

8

8

.

5

 

}

,




[

B

E

L

E

C

O

H

E

N

_

T

Y

P

E

]

 

=

 

{

 

5

1

8

,

 

4

5

6

,

 

-

8

8

.

5

 

}

,




[

F

E

R

A

B

A

L

E

N

_

T

Y

P

E

]

 

=

 

{

 

4

6

1

,

 

4

9

8

,

 

-

8

5

.

8

7

5

 

}

,




}

;







l

o

c

a

l

 

s

i

g

n

a

l

s

 

=

 

{

}

;




l

o

c

a

l

 

k

i

l

l

s

 

=

 

0

;




l

o

c

a

l

 

s

p

a

w

n

s

 

=

 

{

 

A

L

R

A

N

D

E

R

I

S

A

N

_

T

Y

P

E

,

 

B

E

L

E

C

O

H

E

N

_

T

Y

P

E

,

 

F

E

R

A

B

A

L

E

N

_

T

Y

P

E

 

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

 

R

e

p

o

p

I

s

l

a

n

d

(

)




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

C

A

S

T

E

L

L

A

N

_

S

P

A

W

N

I

D

S

)

 

d

o




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

R

e

p

o

p

(

)

;










k

i

l

l

s

 

=

 

0

;







f

o

r

 

i

 

=

 

2

,

 

4

 

d

o




s

i

g

n

a

l

s

[

i

]

 

=

 

n

i

l

;










s

p

a

w

n

s

[

1

]

 

=

 

e

q

.

C

h

o

o

s

e

R

a

n

d

o

m

(

A

L

R

A

N

D

E

R

I

S

A

N

_

T

Y

P

E

,

 

B

E

L

E

C

O

H

E

N

_

T

Y

P

E

,

 

F

E

R

A

B

A

L

E

N

_

T

Y

P

E

)

;




s

p

a

w

n

s

[

2

]

 

=

 

n

i

l

;




s

p

a

w

n

s

[

3

]

 

=

 

n

i

l

;




w

h

i

l

e

 

(

 

n

o

t

 

s

p

a

w

n

s

[

2

]

 

)

 

d

o




s

p

a

w

n

s

[

2

]

 

=

 

e

q

.

C

h

o

o

s

e

R

a

n

d

o

m

(

A

L

R

A

N

D

E

R

I

S

A

N

_

T

Y

P

E

,

 

B

E

L

E

C

O

H

E

N

_

T

Y

P

E

,

 

F

E

R

A

B

A

L

E

N

_

T

Y

P

E

)

;




i

f

 

(

 

s

p

a

w

n

s

[

2

]

 

=

=

 

s

p

a

w

n

s

[

1

]

 

)

 

t

h

e

n




s

p

a

w

n

s

[

2

]

 

=

 

n

i

l

;










w

h

i

l

e

 

(

 

n

o

t

 

s

p

a

w

n

s

[

3

]

 

)

 

d

o




s

p

a

w

n

s

[

3

]

 

=

 

e

q

.

C

h

o

o

s

e

R

a

n

d

o

m

(

A

L

R

A

N

D

E

R

I

S

A

N

_

T

Y

P

E

,

 

B

E

L

E

C

O

H

E

N

_

T

Y

P

E

,

 

F

E

R

A

B

A

L

E

N

_

T

Y

P

E

)

;




i

f

 

(

 

s

p

a

w

n

s

[

3

]

 

=

=

 

s

p

a

w

n

s

[

1

]

 

o

r

 

s

p

a

w

n

s

[

3

]

 

=

=

 

s

p

a

w

n

s

[

2

]

 

)

 

t

h

e

n




s

p

a

w

n

s

[

3

]

 

=

 

n

i

l

;






















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




*

*

S

e

t

 

a

 

t

i

m

e

r

*

*

 

n

a

m

e

d

 

*

c

a

s

t

e

l

l

a

n

_

r

e

p

o

p

*

 

f

o

r

 

1

0

8

0

 

s

e

c

o

n

d

s
















#

#

 

T

i

m

e

r

(

s

)







i

f

 

(

 

e

.

t

i

m

e

r

 

=

=

 

"

c

a

s

t

e

l

l

a

n

_

r

e

p

o

p

"

 

)

 

t

h

e

n




R

e

p

o

p

I

s

l

a

n

d

(

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

C

A

S

T

E

L

L

A

N

_

T

Y

P

E

)

 

)

 

t

h

e

n




*

*

S

e

t

 

a

 

t

i

m

e

r

*

*

 

n

a

m

e

d

 

*

c

a

s

t

e

l

l

a

n

_

r

e

p

o

p

*

 

f

o

r

 

1

0

8

0

 

s

e

c

o

n

d

s




e

l

s

e




*

*

S

e

t

 

a

 

t

i

m

e

r

*

*

 

n

a

m

e

d

 

*

c

a

s

t

e

l

l

a

n

_

r

e

p

o

p

*

 

f

o

r

 

1

0

8

0

0

 

s

e

c

o

n

d

s










k

i

l

l

s

 

=

 

k

i

l

l

s

 

+

 

1

;







l

o

c

a

l

 

t

,

 

m

o

b

;




i

f

 

(

 

k

i

l

l

s

 

=

=

 

5

 

)

 

t

h

e

n




t

 

=

 

s

p

a

w

n

s

[

1

]

;




e

l

s

e

i

f

 

(

 

k

i

l

l

s

 

=

=

 

1

0

 

)

 

t

h

e

n




t

 

=

 

s

p

a

w

n

s

[

2

]

;




e

l

s

e

i

f

 

(

 

k

i

l

l

s

 

=

=

 

1

5

 

)

 

t

h

e

n




t

 

=

 

s

p

a

w

n

s

[

3

]

;










i

f

 

(

 

t

 

)

 

t

h

e

n




l

o

c

 

=

 

L

O

C

S

[

t

]

;




m

o

b

 

=

 

e

q

.

u

n

i

q

u

e

_

s

p

a

w

n

(

t

,

 

0

,

 

0

,

 

L

O

C

S

[

t

]

[

1

]

,

 

L

O

C

S

[

t

]

[

2

]

,

 

L

O

C

S

[

t

]

[

3

]

,

 

0

)

;




i

f

 

(

 

m

o

b

 

a

n

d

 

m

o

b

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




e

q

.

d

e

b

u

g

(

m

o

b

:

G

e

t

C

l

e

a

n

N

a

m

e

(

)

.

.

"

 

s

p

a

w

n

e

d

"

)

;













e

l

s

e




s

i

g

n

a

l

s

[

e

.

s

i

g

n

a

l

]

 

=

 

1

;







i

f

 

(

 

s

i

g

n

a

l

s

[

2

]

 

a

n

d

 

s

i

g

n

a

l

s

[

3

]

 

a

n

d

 

s

i

g

n

a

l

s

[

4

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




l

o

c

a

l

 

m

o

b

;







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

C

H

A

M

B

E

R

L

A

I

N

_

T

Y

P

E

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

A

P

P

R

E

N

T

I

C

E

_

T

Y

P

E

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

A

R

M

O

R

_

G

U

Y

_

T

Y

P

E

)

 

)

 

t

h

e

n




m

o

b

 

=

 

e

q

.

s

p

a

w

n

2

(

C

H

A

M

B

E

R

L

A

I

N

_

T

Y

P

E

,

 

0

,

 

0

,

 

4

5

7

,

 

4

1

2

,

 

-

8

8

.

6

2

2

,

 

0

)

;




e

l

s

e




m

o

b

 

=

 

e

q

.

s

p

a

w

n

2

(

A

P

P

R

E

N

T

I

C

E

_

T

Y

P

E

,

 

0

,

 

0

,

 

4

5

7

,

 

4

1

2

,

 

-

8

8

.

6

2

2

,

 

0

)

;







i

f

 

(

 

m

o

b

 

a

n

d

 

m

o

b

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




e

q

.

d

e

b

u

g

(

m

o

b

:

G

e

t

C

l

e

a

n

N

a

m

e

(

)

.

.

"

 

s

p

a

w

n

e

d

"

)

;

















