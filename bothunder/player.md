











l

o

c

a

l

 

r

a

i

d

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

 

g

a

r

g

s

 

=

 

0

;

	







f

u

n

c

t

i

o

n

 

F

i

n

d

R

a

i

d

(

e

)




l

o

c

a

l

 

m

y

R

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




l

o

c

a

l

 

m

y

G

r

o

u

p

 

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

G

r

o

u

p

(

)

;




l

o

c

a

l

 

r

i

d

,

 

g

i

d

 

=

 

0

,

 

0

;




l

o

c

a

l

 

n

o

w

 

=

 

e

q

.

c

l

o

c

k

(

)

;







i

f

 

(

 

m

y

R

a

i

d

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




r

i

d

 

=

 

m

y

R

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

;




e

l

s

e

i

f

 

(

 

m

y

G

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




g

i

d

 

=

 

m

y

G

r

o

u

p

:

G

e

t

I

D

(

)

;










f

o

r

 

i

,

 

r

a

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

r

a

i

d

s

)

 

d

o







i

f

 

(

 

r

i

d

 

>

 

0

 

a

n

d

 

r

a

i

d

.

r

i

d

 

=

=

 

r

i

d

 

a

n

d

 

n

o

w

 

<

 

r

a

i

d

.

e

x

p

i

r

e

 

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

 

i

;







e

l

s

e

i

f

 

(

 

g

i

d

 

>

 

0

 

a

n

d

 

r

a

i

d

.

g

i

d

 

=

=

 

g

i

d

 

a

n

d

 

n

o

w

 

<

 

r

a

i

d

.

e

x

p

i

r

e

 

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

 

i

;













r

e

t

u

r

n

 

n

i

l

;










f

u

n

c

t

i

o

n

 

A

d

d

R

a

i

d

(

e

)




l

o

c

a

l

 

m

y

R

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




l

o

c

a

l

 

m

y

G

r

o

u

p

 

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

G

r

o

u

p

(

)

;




l

o

c

a

l

 

r

i

d

,

 

g

i

d

 

=

 

0

,

 

0

;




l

o

c

a

l

 

i

d

x

 

=

 

F

i

n

d

R

a

i

d

(

e

)

;




l

o

c

a

l

 

n

o

w

 

=

 

e

q

.

c

l

o

c

k

(

)

;







i

f

 

(

 

m

y

R

a

i

d

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




r

i

d

 

=

 

m

y

R

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

;




e

l

s

e

i

f

 

(

 

m

y

G

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




g

i

d

 

=

 

m

y

G

r

o

u

p

:

G

e

t

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

x

 

)

 

t

h

e

n




r

a

i

d

s

[

i

d

x

]

.

e

x

p

i

r

e

 

=

 

n

o

w

 

+

 

6

0

;




e

l

s

e




i

f

 

(

 

r

i

d

 

>

 

0

 

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

"

R

a

i

d

 

I

D

 

"

.

.

r

i

d

.

.

"

 

m

a

y

 

n

o

w

 

e

n

t

e

r

 

A

g

n

a

r

r

'

s

 

t

o

w

e

r

 

f

o

r

 

t

h

e

 

n

e

x

t

 

6

0

 

s

e

c

o

n

d

s

"

)

;




t

a

b

l

e

.

i

n

s

e

r

t

(

r

a

i

d

s

,

 

{

 

[

"

r

i

d

"

]

 

=

 

r

i

d

,

 

[

"

g

i

d

"

]

 

=

 

0

,

 

[

"

e

x

p

i

r

e

"

]

 

=

 

n

o

w

+

6

0

 

}

)

;




i

d

x

 

=

 

#

r

a

i

d

s

;




e

l

s

e

i

f

 

(

 

g

i

d

 

>

 

0

 

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

"

G

r

o

u

p

 

I

D

 

"

.

.

g

i

d

.

.

"

 

m

a

y

 

n

o

w

 

e

n

t

e

r

 

A

g

n

a

r

r

'

s

 

t

o

w

e

r

 

f

o

r

 

t

h

e

 

n

e

x

t

 

6

0

 

s

e

c

o

n

d

s

"

)

;




t

a

b

l

e

.

i

n

s

e

r

t

(

r

a

i

d

s

,

 

{

 

[

"

r

i

d

"

]

 

=

 

0

,

 

[

"

g

i

d

"

]

 

=

 

g

i

d

,

 

[

"

e

x

p

i

r

e

"

]

 

=

 

n

o

w

+

6

0

 

}

)

;




i

d

x

 

=

 

#

r

a

i

d

s

;
















l

o

c

a

l

 

i

 

=

 

#

r

a

i

d

s

;




w

h

i

l

e

 

(

 

i

 

>

 

0

 

)

 

d

o




i

f

 

(

 

r

a

i

d

s

[

i

]

.

e

x

p

i

r

e

 

<

 

n

o

w

 

)

 

t

h

e

n




t

a

b

l

e

.

r

e

m

o

v

e

(

r

a

i

d

s

,

 

i

)

;







i

 

=

 

i

 

-

 

1

;










r

e

t

u

r

n

 

i

d

x

;










f

u

n

c

t

i

o

n

 

A

g

g

r

o

G

a

r

g

o

y

l

e

s

(

p

l

a

y

e

r

,

 

d

o

o

r

_

i

d

)







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

 

=

=

 

5

1

 

)

 

t

h

e

n







g

a

r

g

s

 

=

 

g

a

r

g

s

 

+

 

1

;







i

f

 

(

 

g

a

r

g

s

 

=

=

 

1

 

)

 

t

h

e

n




p

l

a

y

e

r

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

M

a

g

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

 

s

h

o

o

t

 

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

l

s

e

i

f

 

(

 

g

a

r

g

s

 

=

=

 

2

 

)

 

t

h

e

n




p

l

a

y

e

r

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

 

h

e

a

r

 

t

h

e

 

c

r

a

c

k

i

n

g

 

o

f

 

s

t

o

n

e

s

 

a

r

o

u

n

d

 

y

o

u

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

l

s

e




g

a

r

g

s

 

=

 

0

;













*

*

S

i

g

n

a

l

e

d

 

t

o

:

*

*

 

 

[

A

 

s

t

o

r

m

 

w

a

t

c

h

e

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

9

1

1

3

)










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

z

o

n

e

,

 

c

l

i

e

n

t

,

 

d

i

s

t

,

 

x

,

 

y

,

 

z

,

 

h

)




l

o

c

a

l

 

g

r

o

u

p

 

=

 

c

l

i

e

n

t

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

 

c

l

i

e

n

t

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

 

g

r

o

u

p

 

a

n

d

 

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

 

>

 

0

 

)

 

t

h

e

n




f

o

r

 

i

 

=

 

0

,

 

5

 

d

o




l

o

c

a

l

 

m

e

m

b

e

r

 

=

 

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

 

m

e

m

b

e

r

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

 

m

e

m

b

e

r

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

c

l

i

e

n

t

:

G

e

t

X

(

)

,

 

c

l

i

e

n

t

:

G

e

t

Y

(

)

,

 

c

l

i

e

n

t

:

G

e

t

Z

(

)

)

 

<

 

d

i

s

t

 

)

 

t

h

e

n




m

e

m

b

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

z

o

n

e

,

 

x

,

 

y

,

 

z

,

 

h

*

2

)

;




i

f

 

(

 

m

e

m

b

e

r

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

 

)

 

t

h

e

n




i

f

 

(

 

m

e

m

b

e

r

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




m

e

m

b

e

r

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

B

u

f

f

F

a

d

e

B

y

E

f

f

e

c

t

(

2

2

)

;

 




e

l

s

e




m

e

m

b

e

r

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

x

,

 

y

,

 

z

,

 

0

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

R

e

m

o

v

e

F

r

o

m

H

a

t

e

L

i

s

t

s

(

m

e

m

b

e

r

)

;
















e

l

s

e

i

f

 

(

 

r

a

i

d

 

a

n

d

 

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

a

i

d

G

r

o

u

p

I

D

 

=

 

r

a

i

d

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

c

l

i

e

n

t

:

G

e

t

N

a

m

e

(

)

)

;




l

o

c

a

l

 

m

e

m

b

e

r

;




f

o

r

 

i

 

=

 

0

,

 

7

1

 

d

o




m

e

m

b

e

r

 

=

 

r

a

i

d

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

;







i

f

 

(

 

m

e

m

b

e

r

 

a

n

d

 

m

e

m

b

e

r

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

a

i

d

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

m

e

m

b

e

r

:

G

e

t

N

a

m

e

(

)

)

 

=

=

 

r

a

i

d

G

r

o

u

p

I

D

 

)

 

t

h

e

n







i

f

 

(

 

m

e

m

b

e

r

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

c

l

i

e

n

t

:

G

e

t

X

(

)

,

 

c

l

i

e

n

t

:

G

e

t

Y

(

)

,

 

c

l

i

e

n

t

:

G

e

t

Z

(

)

)

 

<

 

d

i

s

t

 

)

 

t

h

e

n




m

e

m

b

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

z

o

n

e

,

 

x

,

 

y

,

 

z

,

 

h

*

2

)

;




i

f

 

(

 

m

e

m

b

e

r

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

 

)

 

t

h

e

n




i

f

 

(

 

m

e

m

b

e

r

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




m

e

m

b

e

r

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

B

u

f

f

F

a

d

e

B

y

E

f

f

e

c

t

(

2

2

)

;

 




e

l

s

e




m

e

m

b

e

r

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

x

,

 

y

,

 

z

,

 

0

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

R

e

m

o

v

e

F

r

o

m

H

a

t

e

L

i

s

t

s

(

m

e

m

b

e

r

)

;













e

l

s

e




c

l

i

e

n

t

:

M

o

v

e

P

C

(

z

o

n

e

,

 

x

,

 

y

,

 

z

,

 

h

*

2

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




c

l

i

e

n

t

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

B

u

f

f

F

a

d

e

B

y

E

f

f

e

c

t

(

2

2

)

;

 




e

l

s

e




c

l

i

e

n

t

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

x

,

 

y

,

 

z

,

 

0

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

R

e

m

o

v

e

F

r

o

m

H

a

t

e

L

i

s

t

s

(

c

l

i

e

n

t

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

 

=

=

 

5

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

4

3

3

 

)

 

t

h

e

n




A

d

d

R

a

i

d

(

e

)

;










i

f

 

(

 

F

i

n

d

R

a

i

d

(

e

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

4

3

3

 

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

o

v

e

P

C

(

2

0

9

,

 

-

7

6

5

,

 

-

1

7

3

5

,

 

1

2

7

0

,

 

1

9

2

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

B

u

f

f

F

a

d

e

B

y

E

f

f

e

c

t

(

2

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

-

7

6

5

,

 

-

1

7

3

5

,

 

1

2

7

0

,

 

0

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

R

e

m

o

v

e

F

r

o

m

H

a

t

e

L

i

s

t

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







e

l

s

e




A

g

g

r

o

G

a

r

g

o

y

l

e

s

(

e

.

s

e

l

f

,

 

d

o

o

r

_

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

4

2

5

 

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

G

M

(

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

2

0

9

,

 

e

.

s

e

l

f

,

 

1

0

0

,

 

8

5

,

 

1

4

5

,

 

6

3

5

,

 

6

4

)










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

 

9

4

2

5

 

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

G

M

(

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

2

0

9

,

 

e

.

s

e

l

f

,

 

1

0

0

,

 

-

8

3

0

,

 

-

8

6

5

,

 

1

3

7

5

,

 

6

4

)










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

4

2

5

 

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

G

M

(

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

2

0

9

,

 

e

.

s

e

l

f

,

 

1

0

0

,

 

-

3

5

0

,

 

-

2

2

0

0

,

 

1

9

5

5

,

 

1

2

8

)










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

7

 

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

4

2

5

 

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

G

M

(

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

2

0

9

,

 

e

.

s

e

l

f

,

 

1

0

0

,

 

1

5

0

,

 

-

1

2

2

0

,

 

1

1

2

0

,

 

6

4

)
















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

m

e

r

c

h

a

n

t

(

e

)







i

f

 

(

 

e

.

m

e

r

c

h

a

n

t

_

t

y

p

e

_

i

d

 

=

=

 

2

0

9

1

5

8

 

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

9

,

 

-

6

6

5

,

 

-

1

7

3

5

,

 

2

2

5

1

,

 

1

9

2

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

-

6

6

5

,

 

-

1

7

3

5

,

 

2

2

5

1

,

 

0

)

;








