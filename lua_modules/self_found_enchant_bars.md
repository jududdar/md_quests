l

o

c

a

l

 

e

n

c

h

a

n

t

_

b

a

r

s

 

=

 

{

}







f

u

n

c

t

i

o

n

 

e

n

c

h

a

n

t

_

b

a

r

s

.

_

c

h

e

c

k

_

b

a

r

_

t

y

p

e

(

i

t

e

m

_

l

i

b

,

 

s

e

l

f

,

 

o

t

h

e

r

,

 

t

r

a

d

e

,

 

b

a

r

_

d

a

t

a

)




l

o

c

a

l

 

n

u

m

_

b

a

r

s

 

=

 

0

;




l

o

c

a

l

 

r

e

q

u

i

r

e

d

_

l

e

v

e

l

 

=

 

b

a

r

_

d

a

t

a

.

r

e

q

u

i

r

e

d

_

l

e

v

e

l

;




l

o

c

a

l

 

b

a

r

_

i

d

 

=

 

b

a

r

_

d

a

t

a

.

b

a

r

_

i

d

;




l

o

c

a

l

 

r

e

w

a

r

d

_

i

d

 

=

 

b

a

r

_

d

a

t

a

.

r

e

w

a

r

d

_

i

d

;




l

o

c

a

l

 

p

l

a

t

_

c

o

s

t

 

=

 

b

a

r

_

d

a

t

a

.

p

l

a

t

_

c

o

s

t

;







i

f

 

(

o

t

h

e

r

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

 

r

e

q

u

i

r

e

d

_

l

e

v

e

l

)

 

t

h

e

n







i

f

(

 

*

*

Y

o

u

 

t

u

r

n

 

i

n

:

*

*

 

i

t

e

m

1

 

=

 

b

a

r

_

i

d

,

 

i

t

e

m

2

 

=

 

b

a

r

_

i

d

,

 

i

t

e

m

3

 

=

 

b

a

r

_

i

d

,

 

i

t

e

m

4

 

=

 

b

a

r

_

i

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

 

=

 

p

l

a

t

_

c

o

s

t

 

*

 

4

)

 

t

h

e

n




n

u

m

_

b

a

r

s

 

=

 

4

;




e

l

s

e

i

f

(

 

*

*

Y

o

u

 

t

u

r

n

 

i

n

:

*

*

 

i

t

e

m

1

 

=

 

b

a

r

_

i

d

,

 

i

t

e

m

2

 

=

 

b

a

r

_

i

d

,

 

i

t

e

m

3

 

=

 

b

a

r

_

i

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

 

=

 

p

l

a

t

_

c

o

s

t

 

*

 

3

)

 

t

h

e

n




n

u

m

_

b

a

r

s

 

=

 

3

;




e

l

s

e

i

f

(

 

*

*

Y

o

u

 

t

u

r

n

 

i

n

:

*

*

 

i

t

e

m

1

 

=

 

b

a

r

_

i

d

,

 

i

t

e

m

2

 

=

 

b

a

r

_

i

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

 

=

 

p

l

a

t

_

c

o

s

t

 

*

 

2

)

 

t

h

e

n




n

u

m

_

b

a

r

s

 

=

 

2

;




e

l

s

e

i

f

(

 

*

*

Y

o

u

 

t

u

r

n

 

i

n

:

*

*

 

i

t

e

m

1

 

=

 

b

a

r

_

i

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

 

=

 

p

l

a

t

_

c

o

s

t

)

 

t

h

e

n




n

u

m

_

b

a

r

s

 

=

 

1

;










i

f

(

n

u

m

_

b

a

r

s

 

>

 

0

)

 

t

h

e

n




r

e

p

e

a

t




o

t

h

e

r

:

S

u

m

m

o

n

C

u

r

s

o

r

I

t

e

m

(

r

e

w

a

r

d

_

i

d

,

 

1

)

;

 




n

u

m

_

b

a

r

s

 

=

 

n

u

m

_

b

a

r

s

 

-

 

1

;




u

n

t

i

l

 

n

u

m

_

b

a

r

s

 

=

=

 

0




s

e

l

f

:

S

a

y

(

"

Y

o

u

r

 

m

e

t

a

l

 

h

a

s

 

b

e

e

n

 

s

u

c

c

e

s

s

f

u

l

l

y

 

i

m

b

u

e

d

 

w

i

t

h

 

t

h

e

 

m

y

s

t

i

c

a

l

 

e

n

e

r

g

i

e

s

 

y

o

u

 

s

e

e

k

.

 

B

e

h

o

l

d

,

 

i

t

s

 

t

r

a

n

s

f

o

r

m

a

t

i

o

n

 

i

s

 

c

o

m

p

l

e

t

e

.

 

M

a

y

 

t

h

i

s

 

e

n

c

h

a

n

t

e

d

 

m

e

t

a

l

 

s

e

r

v

e

 

a

s

 

a

 

t

e

s

t

a

m

e

n

t

 

t

o

 

y

o

u

r

 

g

r

o

w

i

n

g

 

i

n

t

e

l

l

e

c

t

 

a

n

d

 

m

a

s

t

e

r

y

 

o

v

e

r

 

t

h

e

 

a

r

c

a

n

e

.

 

U

s

e

 

i

t

 

w

i

t

h

 

k

e

e

n

 

i

n

s

i

g

h

t

 

o

n

 

y

o

u

r

 

j

o

u

r

n

e

y

.

"

)

;




s

e

l

f

:

C

a

s

t

S

p

e

l

l

(

6

6

7

,

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

n

c

h

a

n

t

_

b

a

r

s

.

_

g

e

t

_

b

a

r

_

d

a

t

a

(

)




r

e

t

u

r

n

 

{




{







b

a

r

_

n

a

m

e

 

=

 

"

s

i

l

v

e

r

"

,




c

o

m

p

o

n

e

n

t

_

n

a

m

e

 

=

 

"

S

i

l

v

e

r

 

B

a

r

"

,




b

a

r

_

i

d

 

=

 

1

6

5

0

0

,




r

e

w

a

r

d

_

i

d

 

=

 

1

6

5

0

4

,




p

l

a

t

_

c

o

s

t

 

=

 

5

,




r

e

q

u

i

r

e

d

_

l

e

v

e

l

 

=

 

8




}

,




{







b

a

r

_

n

a

m

e

 

=

 

"

e

l

e

c

t

r

u

m

"

,




c

o

m

p

o

n

e

n

t

_

n

a

m

e

 

=

 

"

E

l

e

c

t

r

u

m

 

B

a

r

"

,




r

e

q

u

i

r

e

d

_

l

e

v

e

l

 

=

 

1

6

,




b

a

r

_

i

d

 

=

 

1

6

5

0

1

,




r

e

w

a

r

d

_

i

d

 

=

 

1

6

5

0

5

,




p

l

a

t

_

c

o

s

t

 

=

 

1

0

,




}

,




{







b

a

r

_

n

a

m

e

 

=

 

"

g

o

l

d

"

,




c

o

m

p

o

n

e

n

t

_

n

a

m

e

 

=

 

"

G

o

l

d

 

B

a

r

"

,




r

e

q

u

i

r

e

d

_

l

e

v

e

l

 

=

 

2

0

,




b

a

r

_

i

d

 

=

 

1

6

5

0

2

,




r

e

w

a

r

d

_

i

d

 

=

 

1

6

5

0

6

,




p

l

a

t

_

c

o

s

t

 

=

 

2

5

,




}

,




{







b

a

r

_

n

a

m

e

 

=

 

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

,




c

o

m

p

o

n

e

n

t

_

n

a

m

e

 

=

 

"

P

l

a

t

i

n

u

m

 

B

a

r

"

,




r

e

q

u

i

r

e

d

_

l

e

v

e

l

 

=

 

2

4

,




b

a

r

_

i

d

 

=

 

1

6

5

0

3

,




r

e

w

a

r

d

_

i

d

 

=

 

1

6

5

0

7

,




p

l

a

t

_

c

o

s

t

 

=

 

5

0

,




}

,




{







b

a

r

_

n

a

m

e

 

=

 

"

v

e

l

i

u

m

"

,




c

o

m

p

o

n

e

n

t

_

n

a

m

e

 

=

 

"

V

e

l

i

u

m

 

B

a

r

"

,




r

e

q

u

i

r

e

d

_

l

e

v

e

l

 

=

 

4

4

,




b

a

r

_

i

d

 

=

 

2

2

0

9

8

,




r

e

w

a

r

d

_

i

d

 

=

 

2

2

0

9

9

,




p

l

a

t

_

c

o

s

t

 

=

 

1

2

5

,




}

,




{







b

a

r

_

n

a

m

e

 

=

 

"

c

l

a

y

"

,




c

o

m

p

o

n

e

n

t

_

n

a

m

e

 

=

 

"

L

a

r

g

e

 

B

l

o

c

k

 

o

f

 

C

l

a

y

"

,




r

e

q

u

i

r

e

d

_

l

e

v

e

l

 

=

 

8

,




b

a

r

_

i

d

 

=

 

1

6

9

0

2

,




r

e

w

a

r

d

_

i

d

 

=

 

1

6

8

9

6

,




p

l

a

t

_

c

o

s

t

 

=

 

5

,




}

,




{







b

a

r

_

n

a

m

e

 

=

 

"

m

i

t

h

r

i

l

"

,




c

o

m

p

o

n

e

n

t

_

n

a

m

e

 

=

 

"

L

a

r

g

e

 

B

r

i

c

k

 

o

f

 

M

i

t

h

r

i

l

"

,




r

e

q

u

i

r

e

d

_

l

e

v

e

l

 

=

 

2

0

,




b

a

r

_

i

d

 

=

 

1

0

4

7

6

,




r

e

w

a

r

d

_

i

d

 

=

 

1

0

4

5

5

,




p

l

a

t

_

c

o

s

t

 

=

 

5

0

,




}

,




{







b

a

r

_

n

a

m

e

 

=

 

"

a

d

a

m

a

n

t

i

t

e

"

,




c

o

m

p

o

n

e

n

t

_

n

a

m

e

 

=

 

"

L

a

r

g

e

 

B

r

i

c

k

 

o

f

 

A

d

a

m

a

n

t

i

t

e

"

,




r

e

q

u

i

r

e

d

_

l

e

v

e

l

 

=

 

2

0

,




b

a

r

_

i

d

 

=

 

1

0

4

7

5

,




r

e

w

a

r

d

_

i

d

 

=

 

1

0

4

4

9

,




p

l

a

t

_

c

o

s

t

 

=

 

6

0

,




}

,




{







b

a

r

_

n

a

m

e

 

=

 

"

s

t

e

e

l

"

,




c

o

m

p

o

n

e

n

t

_

n

a

m

e

 

=

 

"

L

a

r

g

e

 

B

r

i

c

k

 

o

f

 

H

i

g

h

 

Q

u

a

l

i

t

y

 

O

r

e

"

,




r

e

q

u

i

r

e

d

_

l

e

v

e

l

 

=

 

2

0

,




b

a

r

_

i

d

 

=

 

1

0

4

6

9

,




r

e

w

a

r

d

_

i

d

 

=

 

1

0

4

4

0

,




p

l

a

t

_

c

o

s

t

 

=

 

3

0

,




}

,




{







b

a

r

_

n

a

m

e

 

=

 

"

b

r

e

l

l

i

u

m

"

,




c

o

m

p

o

n

e

n

t

_

n

a

m

e

 

=

 

"

L

a

r

g

e

 

B

r

i

c

k

 

o

f

 

B

r

e

l

l

i

u

m

"

,




r

e

q

u

i

r

e

d

_

l

e

v

e

l

 

=

 

2

0

,




b

a

r

_

i

d

 

=

 

1

0

4

7

4

,




r

e

w

a

r

d

_

i

d

 

=

 

1

0

4

3

4

,




p

l

a

t

_

c

o

s

t

 

=

 

3

0

,




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

n

c

h

a

n

t

_

b

a

r

s

.

c

h

e

c

k

_

b

a

r

s

_

q

u

e

s

t

_

d

i

a

l

o

g

u

e

(

s

e

l

f

,

 

o

t

h

e

r

,

 

m

e

s

s

a

g

e

)







l

o

c

a

l

 

i

s

_

s

e

l

f

_

f

o

u

n

d

 

=

 

o

t

h

e

r

:

I

s

S

e

l

f

F

o

u

n

d

(

)

 

=

=

 

1

 

o

r

 

o

t

h

e

r

:

I

s

S

o

l

o

O

n

l

y

(

)

 

=

=

 

1

;




i

f

(

i

s

_

s

e

l

f

_

f

o

u

n

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

 

b

a

r

_

d

a

t

a

_

l

i

s

t

 

=

 

e

n

c

h

a

n

t

_

b

a

r

s

.

_

g

e

t

_

b

a

r

_

d

a

t

a

(

)

;










f

o

r

 

i

n

d

e

x

,

 

b

a

r

_

d

a

t

a

 

i

n

 

i

p

a

i

r

s

(

b

a

r

_

d

a

t

a

_

l

i

s

t

)

 

d

o




e

n

c

h

a

n

t

_

b

a

r

s

.

c

h

e

c

k

_

b

a

r

_

q

u

e

s

t

_

d

i

a

l

o

g

u

e

(

s

e

l

f

,

 

o

t

h

e

r

,

 

m

e

s

s

a

g

e

,

 

b

a

r

_

d

a

t

a

)

;










i

f

(

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

i

(

"

H

a

i

l

"

)

)

 

t

h

e

n




s

e

l

f

:

S

a

y

(

"

A

r

e

 

y

o

u

 

i

n

 

n

e

e

d

 

o

f

 

[

e

n

c

h

a

n

t

m

e

n

t

s

]

?

 

I

f

 

s

o

,

 

I

 

m

a

y

 

b

e

 

a

b

l

e

 

t

o

 

h

e

l

p

 

y

o

u

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

i

(

"

e

n

c

h

a

n

t

m

e

n

t

s

"

)

)

 

t

h

e

n




s

e

l

f

:

S

a

y

(

"

Y

o

u

 

w

i

s

h

 

t

o

 

e

x

p

l

o

r

e

 

t

h

e

 

d

e

e

p

e

r

 

m

y

s

t

e

r

i

e

s

 

o

f

 

m

e

t

a

l

l

u

r

g

y

 

a

n

d

 

m

a

g

i

c

?

 

A

 

n

o

b

l

e

 

p

a

t

h

.

 

T

h

e

 

e

n

c

h

a

n

t

m

e

n

t

 

o

f

 

m

e

t

a

l

 

i

s

 

a

 

d

e

l

i

c

a

t

e

 

a

r

t

.

 

I

 

c

a

n

 

e

n

c

h

a

n

t

 

[

s

i

l

v

e

r

]

,

 

[

e

l

e

c

t

r

u

m

]

,

 

[

g

o

l

d

]

,

 

[

p

l

a

t

i

n

u

m

]

,

 

[

v

e

l

i

u

m

]

,

 

[

c

l

a

y

]

,

 

[

m

i

t

h

r

i

l

]

,

 

[

a

d

a

m

a

n

t

i

t

e

]

,

 

[

s

t

e

e

l

]

,

 

a

n

d

 

[

b

r

e

l

l

i

u

m

]

.

 

W

h

i

c

h

 

d

o

 

y

o

u

 

s

e

e

k

?

"

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

n

c

h

a

n

t

_

b

a

r

s

.

c

h

e

c

k

_

b

a

r

_

q

u

e

s

t

_

d

i

a

l

o

g

u

e

(

s

e

l

f

,

 

o

t

h

e

r

,

 

m

e

s

s

a

g

e

,

 

b

a

r

_

d

a

t

a

)




i

f

(

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

i

(

b

a

r

_

d

a

t

a

.

b

a

r

_

n

a

m

e

)

 

a

n

d

 

n

o

t

 

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

i

(

"

H

a

i

l

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

o

t

h

e

r

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

 

b

a

r

_

d

a

t

a

.

r

e

q

u

i

r

e

d

_

l

e

v

e

l

)

 

t

h

e

n




m

e

s

s

a

g

e

 

=

 

"

P

r

e

s

e

n

t

 

m

e

 

w

i

t

h

 

"

 

.

.

 

b

a

r

_

d

a

t

a

.

p

l

a

t

_

c

o

s

t

 

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

 

p

i

e

c

e

s

 

a

n

d

 

y

o

u

r

 

"

 

.

.

 

b

a

r

_

d

a

t

a

.

c

o

m

p

o

n

e

n

t

_

n

a

m

e

 

.

.




"

,

 

a

n

d

 

w

e

 

s

h

a

l

l

 

b

e

g

i

n

 

t

h

e

 

p

r

o

c

e

s

s

 

o

f

 

i

t

s

 

t

r

a

n

s

f

o

r

m

a

t

i

o

n

.

"

;




s

e

l

f

:

S

a

y

(

m

e

s

s

a

g

e

)

;




e

l

s

e




s

e

l

f

:

S

a

y

(

"

Y

o

u

 

a

r

e

 

a

 

b

i

t

 

t

o

o

 

i

n

e

x

p

e

r

i

e

n

c

e

d

 

t

o

 

b

e

 

d

a

b

b

l

i

n

g

 

i

n

 

s

u

c

h

 

m

a

g

i

c

,

 

a

r

e

n

'

t

 

y

o

u

?

"

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

n

c

h

a

n

t

_

b

a

r

s

.

c

h

e

c

k

_

f

o

r

_

b

a

r

s

_

t

o

_

e

n

c

h

a

n

t

(

i

t

e

m

_

l

i

b

,

 

s

e

l

f

,

 

o

t

h

e

r

,

 

t

r

a

d

e

)







l

o

c

a

l

 

i

s

_

s

e

l

f

_

f

o

u

n

d

 

=

 

o

t

h

e

r

:

I

s

S

e

l

f

F

o

u

n

d

(

)

 

=

=

 

1

 

o

r

 

o

t

h

e

r

:

I

s

S

o

l

o

O

n

l

y

(

)

 

=

=

 

1

;







l

o

c

a

l

 

b

a

r

_

d

a

t

a

_

l

i

s

t

 

=

 

e

n

c

h

a

n

t

_

b

a

r

s

.

_

g

e

t

_

b

a

r

_

d

a

t

a

(

)

;







i

f

(

i

s

_

s

e

l

f

_

f

o

u

n

d

)

 

t

h

e

n







f

o

r

 

i

n

d

e

x

,

 

b

a

r

_

d

a

t

a

 

i

n

 

i

p

a

i

r

s

(

b

a

r

_

d

a

t

a

_

l

i

s

t

)

 

d

o




e

n

c

h

a

n

t

_

b

a

r

s

.

_

c

h

e

c

k

_

b

a

r

_

t

y

p

e

(

i

t

e

m

_

l

i

b

,

 

s

e

l

f

,

 

o

t

h

e

r

,

 

t

r

a

d

e

,

 

b

a

r

_

d

a

t

a

)

;
















r

e

t

u

r

n

 

e

n

c

h

a

n

t

_

b

a

r

s

;