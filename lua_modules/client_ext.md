f

u

n

c

t

i

o

n

 

C

l

i

e

n

t

:

F

a

c

t

i

o

n

(

n

p

c

,

 

f

a

c

t

i

o

n

_

i

d

,

 

f

a

c

t

i

o

n

_

v

a

l

u

e

,

 

t

e

m

p

)




t

e

m

p

 

=

 

t

e

m

p

 

o

r

 

0

;







i

f

(

n

p

c

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




r

e

t

u

r

n

;










s

e

l

f

:

S

e

t

F

a

c

t

i

o

n

L

e

v

e

l

2

(

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

,

 

f

a

c

t

i

o

n

_

i

d

,

 

f

a

c

t

i

o

n

_

v

a

l

u

e

,

 

t

e

m

p

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

 

C

l

i

e

n

t

:

G

i

v

e

C

a

s

h

(

c

o

p

p

e

r

,

 

s

i

l

v

e

r

,

 

g

o

l

d

,

 

p

l

a

t

i

n

u

m

)




c

o

p

p

e

r

 

=

 

c

o

p

p

e

r

 

o

r

 

0

;




s

i

l

v

e

r

 

=

 

s

i

l

v

e

r

 

o

r

 

0

;




g

o

l

d

 

=

 

g

o

l

d

 

o

r

 

0

;




p

l

a

t

i

n

u

m

 

=

 

p

l

a

t

i

n

u

m

 

o

r

 

0

;







i

f

(

c

o

p

p

e

r

 

=

=

 

0

 

a

n

d

 

s

i

l

v

e

r

 

=

=

 

0

 

a

n

d

 

g

o

l

d

 

=

=

 

0

 

a

n

d

 

p

l

a

t

i

n

u

m

 

=

=

 

0

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










s

e

l

f

:

A

d

d

M

o

n

e

y

T

o

P

P

(

c

o

p

p

e

r

,

 

s

i

l

v

e

r

,

 

g

o

l

d

,

 

p

l

a

t

i

n

u

m

,

 

t

r

u

e

)

;







l

o

c

a

l

 

t

m

p

 

=

 

"

Y

o

u

 

r

e

c

e

i

v

e

 

"

;




l

o

c

a

l

 

f

i

r

s

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

p

l

a

t

i

n

u

m

 

>

 

0

)

 

t

h

e

n




t

m

p

 

=

 

t

m

p

 

.

.

 

t

o

s

t

r

i

n

g

(

p

l

a

t

i

n

u

m

)

 

.

.

 

"

 

p

l

a

t

i

n

u

m

"

;




f

i

r

s

t

 

=

 

f

a

l

s

e

;










i

f

(

g

o

l

d

 

>

 

0

)

 

t

h

e

n




i

f

(

f

i

r

s

t

)

 

t

h

e

n




f

i

r

s

t

 

=

 

f

a

l

s

e

;




e

l

s

e




t

m

p

 

=

 

t

m

p

 

.

.

 

"

,

 

"

;










t

m

p

 

=

 

t

m

p

 

.

.

 

t

o

s

t

r

i

n

g

(

g

o

l

d

)

 

.

.

 

"

 

g

o

l

d

"

;










i

f

(

s

i

l

v

e

r

 

>

 

0

)

 

t

h

e

n




i

f

(

f

i

r

s

t

)

 

t

h

e

n




f

i

r

s

t

 

=

 

f

a

l

s

e

;




e

l

s

e




t

m

p

 

=

 

t

m

p

 

.

.

 

"

,

 

"

;










t

m

p

 

=

 

t

m

p

 

.

.

 

t

o

s

t

r

i

n

g

(

s

i

l

v

e

r

)

 

.

.

 

"

 

s

i

l

v

e

r

"

;










i

f

(

c

o

p

p

e

r

 

>

 

0

)

 

t

h

e

n




i

f

(

f

i

r

s

t

)

 

t

h

e

n




f

i

r

s

t

 

=

 

f

a

l

s

e

;




e

l

s

e




t

m

p

 

=

 

t

m

p

 

.

.

 

"

,

 

"

;










t

m

p

 

=

 

t

m

p

 

.

.

 

t

o

s

t

r

i

n

g

(

c

o

p

p

e

r

)

 

.

.

 

"

 

c

o

p

p

e

r

"

;










t

m

p

 

=

 

t

m

p

 

.

.

 

"

 

p

i

e

c

e

s

.

"

;







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

6

0

,

 

t

m

p

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

 

C

l

i

e

n

t

:

D

i

n

g

(

)




s

e

l

f

:

S

e

n

d

S

o

u

n

d

(

1

4

1

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

 

C

l

i

e

n

t

:

G

e

t

F

a

c

t

i

o

n

(

n

p

c

)




r

e

t

u

r

n

 

s

e

l

f

:

G

e

t

F

a

c

t

i

o

n

L

e

v

e

l

(

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

,

 

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

c

e

(

)

,

 

s

e

l

f

:

G

e

t

C

l

a

s

s

(

)

,

 

s

e

l

f

:

G

e

t

D

e

i

t

y

(

)

,

 

n

p

c

:

G

e

t

P

r

i

m

a

r

y

F

a

c

t

i

o

n

(

)

,

 

n

p

c

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

 

C

l

i

e

n

t

:

C

l

a

s

s

(

)




l

o

c

a

l

 

c

l

a

s

s

 

=

 

s

e

l

f

:

G

e

t

C

l

a

s

s

(

)

;







d

o




l

o

c

a

l

 

c

 

=

 

{




[

1

]

 

=

 

"

W

a

r

r

i

o

r

"

,




[

2

]

 

=

 

"

C

l

e

r

i

c

"

,




[

3

]

 

=

 

"

P

a

l

a

d

i

n

"

,




[

4

]

 

=

 

"

R

a

n

g

e

r

"

,




[

5

]

 

=

 

"

S

h

a

d

o

w

k

n

i

g

h

t

"

,




[

6

]

 

=

 

"

D

r

u

i

d

"

,




[

7

]

 

=

 

"

M

o

n

k

"

,




[

8

]

 

=

 

"

B

a

r

d

"

,




[

9

]

 

=

 

"

R

o

g

u

e

"

,




[

1

0

]

 

=

 

"

S

h

a

m

a

n

"

,




[

1

1

]

 

=

 

"

N

e

c

r

o

m

a

n

c

e

r

"

,




[

1

2

]

 

=

 

"

W

i

z

a

r

d

"

,




[

1

3

]

 

=

 

"

M

a

g

i

c

i

a

n

"

,




[

1

4

]

 

=

 

"

E

n

c

h

a

n

t

e

r

"

,




[

1

5

]

 

=

 

"

B

e

a

s

t

l

o

r

d

"

,




[

1

6

]

 

=

 

"

B

e

r

s

e

r

k

e

r

"




}







r

e

t

u

r

n

 

c

[

c

l

a

s

s

]

;













f

u

n

c

t

i

o

n

 

C

l

i

e

n

t

:

R

a

c

e

(

)




l

o

c

a

l

 

r

a

c

e

 

=

 

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

c

e

(

)

;







d

o




l

o

c

a

l

 

r

 

=

 

{




[

1

]

 

=

 

"

H

u

m

a

n

"

,




[

2

]

 

=

 

"

B

a

r

b

a

r

i

a

n

"

,




[

3

]

 

=

 

"

E

r

u

d

i

t

e

"

,




[

4

]

 

=

 

"

W

o

o

d

 

E

l

f

"

,




[

5

]

 

=

 

"

H

i

g

h

 

E

l

f

"

,




[

6

]

 

=

 

"

D

a

r

k

 

E

l

f

"

,




[

7

]

 

=

 

"

H

a

l

f

 

E

l

f

"

,




[

8

]

 

=

 

"

D

w

a

r

f

"

,




[

9

]

 

=

 

"

T

r

o

l

l

"

,




[

1

0

]

 

=

 

"

O

g

r

e

"

,




[

1

1

]

 

=

 

"

H

a

l

f

l

i

n

g

"

,




[

1

2

]

 

=

 

"

G

n

o

m

e

"

,




[

1

4

]

 

=

 

"

W

e

r

e

w

o

l

f

"

,




[

7

4

]

 

=

 

"

F

r

o

g

l

o

k

"

,




[

7

5

]

 

=

 

"

E

l

e

m

e

n

t

a

l

"

,




[

1

0

8

]

 

=

 

"

E

y

e

 

o

f

 

Z

o

m

m

"

,




[

1

2

0

]

 

=

 

"

W

o

l

f

 

E

l

e

m

e

n

t

a

l

"

,




[

1

2

8

]

 

=

 

"

I

k

s

a

r

"

,




[

1

3

0

]

 

=

 

"

V

a

h

 

S

h

i

r

"

,




[

1

6

1

]

 

=

 

"

I

k

s

a

r

 

S

k

e

l

e

t

o

n

"

,




[

3

3

0

]

 

=

 

"

F

r

o

g

l

o

k

"

,




[

3

6

7

]

 

=

 

"

S

k

e

l

e

t

o

n

"

,




[

5

2

2

]

 

=

 

"

D

r

a

k

k

i

n

"

,




[

'

?

'

]

 

=

 

"

U

n

k

n

o

w

n

"




}







r

e

t

u

r

n

 

r

[

r

a

c

e

]

;













f

u

n

c

t

i

o

n

 

C

l

i

e

n

t

:

H

a

s

I

t

e

m

(

i

t

e

m

i

d

)










f

o

r

 

i

 

=

 

0

,

 

3

0

,

 

1

 

d

o




l

o

c

a

l

 

t

h

i

s

i

t

e

m

 

=

 

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

i

)

;




i

f

(

t

h

i

s

i

t

e

m

 

=

=

 

i

t

e

m

i

d

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
















i

f

 

(

s

e

l

f

:

F

i

n

d

O

n

C

u

r

s

o

r

(

i

t

e

m

i

d

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

 

t

r

u

e

;













f

o

r

 

i

 

=

 

2

5

0

,

 

3

3

9

,

 

1

 

d

o




l

o

c

a

l

 

t

h

i

s

i

t

e

m

 

=

 

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

i

)

;




i

f

(

t

h

i

s

i

t

e

m

 

=

=

 

i

t

e

m

i

d

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
















f

o

r

 

i

 

=

 

2

0

0

0

,

 

2

0

0

7

,

 

1

 

d

o




l

o

c

a

l

 

t

h

i

s

i

t

e

m

 

=

 

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

i

)

;




i

f

(

t

h

i

s

i

t

e

m

 

=

=

 

i

t

e

m

i

d

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
















f

o

r

 

i

 

=

 

2

0

3

0

,

 

2

1

0

9

,

 

1

 

d

o




l

o

c

a

l

 

t

h

i

s

i

t

e

m

 

=

 

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

i

)

;




i

f

(

t

h

i

s

i

t

e

m

 

=

=

 

i

t

e

m

i

d

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
















f

o

r

 

i

 

=

 

2

5

3

1

,

 

2

5

5

0

,

 

1

 

d

o




l

o

c

a

l

 

t

h

i

s

i

t

e

m

 

=

 

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

i

)

;




i

f

(

t

h

i

s

i

t

e

m

 

=

=

 

i

t

e

m

i

d

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










f

u

n

c

t

i

o

n

 

C

l

i

e

n

t

:

F

o

r

e

a

c

h

H

a

t

e

L

i

s

t

(

f

u

n

c

,

 

c

o

n

d

)




c

o

n

d

 

=

 

c

o

n

d

 

o

r

 

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

,

 

h

a

t

e

,

 

d

a

m

a

g

e

,

 

f

r

e

n

z

y

)

 

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

 

e

n

d

;




l

o

c

a

l

 

l

s

t

 

=

 

s

e

l

f

:

G

e

t

H

a

t

e

L

i

s

t

(

)

;




f

o

r

 

e

n

t

 

i

n

 

l

s

t

.

e

n

t

r

i

e

s

 

d

o




l

o

c

a

l

 

c

v

 

=

 

c

o

n

d

(

e

n

t

.

e

n

t

,

 

e

n

t

.

h

a

t

e

,

 

e

n

t

.

d

a

m

a

g

e

,

 

e

n

t

.

f

r

e

n

z

y

)

;




i

f

(

c

v

)

 

t

h

e

n




f

u

n

c

(

e

n

t

.

e

n

t

,

 

e

n

t

.

h

a

t

e

,

 

e

n

t

.

d

a

m

a

g

e

,

 

e

n

t

.

f

r

e

n

z

y

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

 

C

l

i

e

n

t

:

C

o

u

n

t

H

a

t

e

L

i

s

t

(

c

o

n

d

)




c

o

n

d

 

=

 

c

o

n

d

 

o

r

 

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

,

 

h

a

t

e

,

 

d

a

m

a

g

e

,

 

f

r

e

n

z

y

)

 

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

 

e

n

d

;




l

o

c

a

l

 

l

s

t

 

=

 

s

e

l

f

:

G

e

t

H

a

t

e

L

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

 

r

e

t

 

=

 

0

;




f

o

r

 

e

n

t

 

i

n

 

l

s

t

.

e

n

t

r

i

e

s

 

d

o




l

o

c

a

l

 

c

v

 

=

 

c

o

n

d

(

e

n

t

.

e

n

t

,

 

e

n

t

.

h

a

t

e

,

 

e

n

t

.

d

a

m

a

g

e

,

 

e

n

t

.

f

r

e

n

z

y

)

;




i

f

(

c

v

)

 

t

h

e

n




r

e

t

 

=

 

r

e

t

 

+

 

1

;













r

e

t

u

r

n

 

r

e

t

;


