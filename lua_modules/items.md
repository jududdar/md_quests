l

o

c

a

l

 

i

t

e

m

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

 

i

t

e

m

s

.

c

h

e

c

k

_

t

u

r

n

_

i

n

(

n

p

c

,

 

t

r

a

d

e

,

 

t

r

a

d

e

_

c

h

e

c

k

,

 

k

e

e

p

i

t

e

m

s

,

 

t

e

x

t

,

 

e

m

o

t

e

)




k

e

e

p

i

t

e

m

s

 

=

 

k

e

e

p

i

t

e

m

s

 

o

r

 

1

;







l

o

c

a

l

 

t

r

a

d

e

_

r

e

t

u

r

n

 

=

 

{

}

;




f

o

r

 

k

e

y

,

 

v

a

l

u

e

 

i

n

 

p

a

i

r

s

(

t

r

a

d

e

)

 

d

o




t

r

a

d

e

_

r

e

t

u

r

n

[

k

e

y

]

 

=

 

v

a

l

u

e

;










i

f

(

t

r

a

d

e

_

r

e

t

u

r

n

[

"

e

n

a

b

l

e

_

m

u

l

t

i

q

u

e

s

t

"

]

 

=

=

 

0

)

 

t

h

e

n




k

e

e

p

i

t

e

m

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

i

t

e

m

s

 

=

 

0

;




i

f

(

t

e

x

t

 

~

=

 

n

i

l

 

o

r

 

e

m

o

t

e

 

~

=

 

n

i

l

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

 

1

,

 

4

 

d

o




l

o

c

a

l

 

k

e

y

 

=

 

"

i

t

e

m

"

 

.

.

 

i

;




i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

 

~

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

 

~

=

 

0

)

 

t

h

e

n




i

f

(

k

e

e

p

i

t

e

m

s

 

=

=

 

0

 

o

r

 

(

k

e

e

p

i

t

e

m

s

 

=

=

 

1

 

a

n

d

 

n

o

t

 

n

p

c

:

G

e

t

Q

u

e

s

t

L

o

o

t

(

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

)

)

)

 

t

h

e

n




r

e

q

u

i

r

e

d

_

i

t

e

m

s

 

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

i

t

e

m

s

 

+

 

1

;
















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

"

.

.

 

n

p

c

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

 

r

e

q

u

i

r

e

s

 

"

 

.

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

i

t

e

m

s

 

.

.

 

"

 

m

o

r

e

 

i

t

e

m

s

 

f

o

r

 

t

h

i

s

 

h

a

n

d

i

n

.

"

,

 

3

)

;










l

o

c

a

l

 

a

c

c

e

p

t

e

d

 

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

k

e

e

p

i

t

e

m

s

 

=

=

 

1

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

 

f

o

u

n

d

i

t

e

m

 

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

 

a

 

=

 

1

,

 

4

 

d

o




l

o

c

a

l

 

a

d

d

 

=

 

t

r

a

d

e

_

r

e

t

u

r

n

[

"

i

t

e

m

"

 

.

.

 

a

]

;




l

o

c

a

l

 

i

t

e

m

i

d

 

=

 

0

;




f

o

r

 

b

 

=

 

1

,

 

4

 

d

o




l

o

c

a

l

 

c

u

r

k

e

y

 

=

 

"

i

t

e

m

"

 

.

.

 

b

;




i

f

(

a

d

d

 

~

=

 

n

i

l

 

a

n

d

 

a

d

d

.

v

a

l

i

d

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

c

u

r

k

e

y

]

 

~

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

c

u

r

k

e

y

]

 

~

=

 

0

)

 

t

h

e

n




i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

c

u

r

k

e

y

]

 

=

=

 

a

d

d

:

G

e

t

I

D

(

)

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

I

t

e

m

 

"

 

.

.

 

a

d

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

 

a

d

d

e

d

 

t

o

 

Q

U

E

S

T

 

l

o

o

t

.

"

,

 

3

)

;




n

p

c

:

A

d

d

Q

u

e

s

t

L

o

o

t

(

a

d

d

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




t

r

a

d

e

_

r

e

t

u

r

n

[

"

i

t

e

m

"

 

.

.

 

a

]

 

=

 

n

i

l

;




f

o

u

n

d

i

t

e

m

 

=

 

t

r

u

e

;




a

c

c

e

p

t

e

d

 

=

 

t

r

u

e

;




i

t

e

m

i

d

 

=

 

0

;







i

f

(

t

e

x

t

 

~

=

 

n

i

l

 

o

r

 

e

m

o

t

e

 

~

=

 

n

i

l

)

 

t

h

e

n




r

e

q

u

i

r

e

d

_

i

t

e

m

s

 

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

i

t

e

m

s

 

-

 

1

;




i

f

(

r

e

q

u

i

r

e

d

_

i

t

e

m

s

 

~

=

 

0

)

 

t

h

e

n




i

f

(

t

e

x

t

 

~

=

 

n

i

l

)

 

t

h

e

n




n

p

c

:

S

a

y

(

"

"

 

.

.

 

t

e

x

t

 

.

.

 

"

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

m

o

t

e

 

~

=

 

n

i

l

)

 

t

h

e

n




n

p

c

:

E

m

o

t

e

(

"

"

 

.

.

 

e

m

o

t

e

 

.

.

 

"

"

)

;
















b

r

e

a

k

;




e

l

s

e




i

t

e

m

i

d

 

=

 

a

d

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

 

a

n

d

 

i

t

e

m

i

d

 

>

 

1

0

0

0

 

a

n

d

 

n

o

t

 

n

p

c

:

G

e

t

P

e

t

L

o

o

t

(

i

t

e

m

i

d

)

 

a

n

d

 

n

o

t

 

n

p

c

:

G

e

t

Q

u

e

s

t

L

o

o

t

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

I

t

e

m

 

"

 

.

.

 

i

t

e

m

i

d

 

.

.

 

"

 

a

d

d

e

d

 

t

o

 

P

E

T

 

l

o

o

t

.

"

,

 

3

)

;




n

p

c

:

A

d

d

P

e

t

L

o

o

t

(

i

t

e

m

i

d

)

;













i

f

(

n

o

t

 

f

o

u

n

d

i

t

e

m

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

"

c

o

p

p

e

r

"

]

 

=

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

"

s

i

l

v

e

r

"

]

 

=

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

"

g

o

l

d

"

]

 

=

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

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

]

 

=

=

 

n

i

l

)

 

t

h

e

n




i

f

(

a

c

c

e

p

t

e

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

"

N

P

C

 

w

a

s

 

h

a

n

d

e

d

 

a

n

 

i

t

e

m

 

i

t

 

d

o

e

s

n

'

t

 

n

e

e

d

,

 

b

u

t

 

a

l

s

o

 

r

e

c

e

i

v

e

d

 

v

a

l

i

d

 

i

t

e

m

s

.

"

,

 

3

)

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

o

r

 

i

 

=

 

1

,

 

4

 

d

o




l

o

c

a

l

 

k

e

y

 

=

 

"

i

t

e

m

"

 

.

.

 

i

;




i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

 

~

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

 

~

=

 

0

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

 

f

o

u

n

d

 

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

 

j

 

=

 

1

,

 

4

 

d

o







l

o

c

a

l

 

i

n

s

t

 

=

 

t

r

a

d

e

_

r

e

t

u

r

n

[

"

i

t

e

m

"

 

.

.

 

j

]

;




i

f

(

i

n

s

t

 

~

=

 

n

i

l

 

a

n

d

 

i

n

s

t

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

 

i

t

e

m

i

d

 

=

 

i

n

s

t

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

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

 

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




i

f

(

k

e

e

p

i

t

e

m

s

 

=

=

 

0

)

 

t

h

e

n




t

r

a

d

e

_

r

e

t

u

r

n

[

"

i

t

e

m

"

 

.

.

 

j

]

 

=

 

I

t

e

m

I

n

s

t

(

)

;







f

o

u

n

d

 

=

 

t

r

u

e

;







i

f

(

k

e

e

p

i

t

e

m

s

 

=

=

 

0

 

a

n

d

 

t

e

x

t

 

~

=

 

n

i

l

)

 

t

h

e

n




r

e

q

u

i

r

e

d

_

i

t

e

m

s

 

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

i

t

e

m

s

 

-

 

1

;




i

f

(

r

e

q

u

i

r

e

d

_

i

t

e

m

s

 

~

=

 

0

)

 

t

h

e

n




n

p

c

:

S

a

y

(

"

"

 

.

.

 

t

e

x

t

 

.

.

 

"

"

)

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




i

f

(

k

e

e

p

i

t

e

m

s

 

=

=

 

1

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

 

h

a

s

i

t

e

m

 

=

 

n

p

c

:

G

e

t

Q

u

e

s

t

L

o

o

t

(

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

)

;




i

f

(

h

a

s

i

t

e

m

)

 

t

h

e

n




f

o

u

n

d

 

=

 

t

r

u

e

;




e

l

s

e




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

A

n

 

i

t

e

m

 

t

h

e

 

N

P

C

 

r

e

q

u

i

r

e

s

 

(

"

 

.

.

 

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

 

.

.

 

"

)

 

w

a

s

 

n

o

t

 

h

a

n

d

e

d

 

t

o

 

t

h

e

m

 

a

n

d

 

i

s

 

n

o

t

 

i

n

 

t

h

e

i

r

 

l

o

o

t

.

"

,

 

3

)

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







e

l

s

e




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

(

N

o

n

-

M

Q

)

 

A

n

 

i

t

e

m

 

t

h

e

 

N

P

C

 

r

e

q

u

i

r

e

s

 

(

"

 

.

.

 

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

 

.

.

 

"

)

 

w

a

s

 

n

o

t

 

h

a

n

d

e

d

 

t

o

 

t

h

e

m

.

"

,

 

3

)

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






















l

o

c

a

l

 

i

t

e

m

1

 

=

 

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

1

"

]

;




l

o

c

a

l

 

i

t

e

m

2

 

=

 

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

2

"

]

;




l

o

c

a

l

 

i

t

e

m

3

 

=

 

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

3

"

]

;




l

o

c

a

l

 

i

t

e

m

4

 

=

 

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

4

"

]

;




i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

1

"

]

 

=

=

 

n

i

l

)

 

t

h

e

n




i

t

e

m

1

 

=

 

0

;







i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

2

"

]

 

=

=

 

n

i

l

)

 

t

h

e

n




i

t

e

m

2

 

=

 

0

;







i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

3

"

]

 

=

=

 

n

i

l

)

 

t

h

e

n




i

t

e

m

3

 

=

 

0

;







i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

4

"

]

 

=

=

 

n

i

l

)

 

t

h

e

n




i

t

e

m

4

 

=

 

0

;










i

f

(

k

e

e

p

i

t

e

m

s

 

=

=

 

1

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

 

c

o

u

n

t

 

=

 

n

p

c

:

H

a

s

R

e

q

u

i

r

e

d

Q

u

e

s

t

L

o

o

t

(

i

t

e

m

1

,

 

i

t

e

m

2

,

 

i

t

e

m

3

,

 

i

t

e

m

4

)

;




i

f

(

n

o

t

 

c

o

u

n

t

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

T

h

e

 

N

P

C

 

d

o

e

s

 

n

o

t

 

h

a

v

e

 

t

h

e

 

r

e

q

u

i

r

e

d

 

n

u

m

b

e

r

 

o

f

 

i

t

e

m

s

 

i

t

 

n

e

e

d

s

.

"

,

 

3

)

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
















l

o

c

a

l

 

t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

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

t

u

r

n

_

m

o

n

e

y

 

=

 

0

;







i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

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

]

 

~

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

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

]

 

~

=

 

0

)

 

t

h

e

n




t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

=

 

t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

+

 

(

t

r

a

d

e

_

c

h

e

c

k

[

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

]

 

*

 

1

0

0

0

)

;










i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

"

g

o

l

d

"

]

 

~

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

"

g

o

l

d

"

]

 

~

=

 

0

)

 

t

h

e

n




t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

=

 

t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

+

 

(

t

r

a

d

e

_

c

h

e

c

k

[

"

g

o

l

d

"

]

 

*

 

1

0

0

)

;










i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

"

s

i

l

v

e

r

"

]

 

~

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

"

s

i

l

v

e

r

"

]

 

~

=

 

0

)

 

t

h

e

n




t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

=

 

t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

+

 

(

t

r

a

d

e

_

c

h

e

c

k

[

"

s

i

l

v

e

r

"

]

 

*

 

1

0

)

;










i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

"

c

o

p

p

e

r

"

]

 

~

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

"

c

o

p

p

e

r

"

]

 

~

=

 

0

)

 

t

h

e

n




t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

=

 

t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

+

 

t

r

a

d

e

_

c

h

e

c

k

[

"

c

o

p

p

e

r

"

]

;










r

e

t

u

r

n

_

m

o

n

e

y

 

=

 

r

e

t

u

r

n

_

m

o

n

e

y

 

+

 

t

r

a

d

e

_

r

e

t

u

r

n

[

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

]

 

*

 

1

0

0

0

 

+

 

t

r

a

d

e

_

r

e

t

u

r

n

[

"

g

o

l

d

"

]

 

*

 

1

0

0

;




r

e

t

u

r

n

_

m

o

n

e

y

 

=

 

r

e

t

u

r

n

_

m

o

n

e

y

 

+

 

t

r

a

d

e

_

r

e

t

u

r

n

[

"

s

i

l

v

e

r

"

]

 

*

 

1

0

 

+

 

t

r

a

d

e

_

r

e

t

u

r

n

[

"

c

o

p

p

e

r

"

]

;







i

f

(

r

e

t

u

r

n

_

m

o

n

e

y

 

<

 

t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

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




r

e

t

u

r

n

_

m

o

n

e

y

 

=

 

r

e

t

u

r

n

_

m

o

n

e

y

 

-

 

t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

;













t

r

a

d

e

.

i

t

e

m

1

 

=

 

t

r

a

d

e

_

r

e

t

u

r

n

.

i

t

e

m

1

;




t

r

a

d

e

.

i

t

e

m

2

 

=

 

t

r

a

d

e

_

r

e

t

u

r

n

.

i

t

e

m

2

;




t

r

a

d

e

.

i

t

e

m

3

 

=

 

t

r

a

d

e

_

r

e

t

u

r

n

.

i

t

e

m

3

;




t

r

a

d

e

.

i

t

e

m

4

 

=

 

t

r

a

d

e

_

r

e

t

u

r

n

.

i

t

e

m

4

;







i

f

(

k

e

e

p

i

t

e

m

s

 

=

=

 

1

)

 

t

h

e

n




n

p

c

:

D

e

l

e

t

e

Q

u

e

s

t

L

o

o

t

(

i

t

e

m

1

,

 

i

t

e

m

2

,

 

i

t

e

m

3

,

 

i

t

e

m

4

)

;










t

r

a

d

e

.

p

l

a

t

i

n

u

m

 

=

 

m

a

t

h

.

f

l

o

o

r

(

r

e

t

u

r

n

_

m

o

n

e

y

 

/

 

1

0

0

0

)

;




r

e

t

u

r

n

_

m

o

n

e

y

 

=

 

r

e

t

u

r

n

_

m

o

n

e

y

 

-

 

(

t

r

a

d

e

.

p

l

a

t

i

n

u

m

 

*

 

1

0

0

0

)

;







t

r

a

d

e

.

g

o

l

d

 

=

 

m

a

t

h

.

f

l

o

o

r

(

r

e

t

u

r

n

_

m

o

n

e

y

 

/

 

1

0

0

)

;




r

e

t

u

r

n

_

m

o

n

e

y

 

=

 

r

e

t

u

r

n

_

m

o

n

e

y

 

-

 

(

t

r

a

d

e

.

g

o

l

d

 

*

 

1

0

0

)

;







t

r

a

d

e

.

s

i

l

v

e

r

 

=

 

m

a

t

h

.

f

l

o

o

r

(

r

e

t

u

r

n

_

m

o

n

e

y

 

/

 

1

0

)

;




r

e

t

u

r

n

_

m

o

n

e

y

 

=

 

r

e

t

u

r

n

_

m

o

n

e

y

 

-

 

(

t

r

a

d

e

.

s

i

l

v

e

r

 

*

 

1

0

)

;







t

r

a

d

e

.

c

o

p

p

e

r

 

=

 

r

e

t

u

r

n

_

m

o

n

e

y

;




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

T

h

e

 

q

u

e

s

t

 

c

o

m

p

l

e

t

e

d

 

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

.

"

,

3

)

;




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

u

n

c

t

i

o

n

 

i

t

e

m

s

.

c

h

e

c

k

_

t

u

r

n

_

i

n

_

n

o

m

q

(

n

p

c

,

 

t

r

a

d

e

,

 

t

r

a

d

e

_

c

h

e

c

k

,

 

k

e

e

p

i

t

e

m

s

,

 

t

e

x

t

,

 

e

m

o

t

e

)




k

e

e

p

i

t

e

m

s

 

=

 

k

e

e

p

i

t

e

m

s

 

o

r

 

1

;







l

o

c

a

l

 

t

r

a

d

e

_

r

e

t

u

r

n

 

=

 

{

}

;




f

o

r

 

k

e

y

,

 

v

a

l

u

e

 

i

n

 

p

a

i

r

s

(

t

r

a

d

e

)

 

d

o




t

r

a

d

e

_

r

e

t

u

r

n

[

k

e

y

]

 

=

 

v

a

l

u

e

;










k

e

e

p

i

t

e

m

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

i

t

e

m

s

 

=

 

0

;




i

f

(

t

e

x

t

 

~

=

 

n

i

l

 

o

r

 

e

m

o

t

e

 

~

=

 

n

i

l

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

 

1

,

 

4

 

d

o




l

o

c

a

l

 

k

e

y

 

=

 

"

i

t

e

m

"

 

.

.

 

i

;




i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

 

~

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

 

~

=

 

0

)

 

t

h

e

n




i

f

(

k

e

e

p

i

t

e

m

s

 

=

=

 

0

 

o

r

 

(

k

e

e

p

i

t

e

m

s

 

=

=

 

1

 

a

n

d

 

n

o

t

 

n

p

c

:

G

e

t

Q

u

e

s

t

L

o

o

t

(

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

)

)

)

 

t

h

e

n




r

e

q

u

i

r

e

d

_

i

t

e

m

s

 

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

i

t

e

m

s

 

+

 

1

;
















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

"

.

.

 

n

p

c

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

 

r

e

q

u

i

r

e

s

 

"

 

.

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

i

t

e

m

s

 

.

.

 

"

 

m

o

r

e

 

i

t

e

m

s

 

f

o

r

 

t

h

i

s

 

h

a

n

d

i

n

.

"

,

 

3

)

;










l

o

c

a

l

 

a

c

c

e

p

t

e

d

 

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

k

e

e

p

i

t

e

m

s

 

=

=

 

1

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

 

f

o

u

n

d

i

t

e

m

 

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

 

a

 

=

 

1

,

 

4

 

d

o




l

o

c

a

l

 

a

d

d

 

=

 

t

r

a

d

e

_

r

e

t

u

r

n

[

"

i

t

e

m

"

 

.

.

 

a

]

;




l

o

c

a

l

 

i

t

e

m

i

d

 

=

 

0

;




f

o

r

 

b

 

=

 

1

,

 

4

 

d

o




l

o

c

a

l

 

c

u

r

k

e

y

 

=

 

"

i

t

e

m

"

 

.

.

 

b

;




i

f

(

a

d

d

 

~

=

 

n

i

l

 

a

n

d

 

a

d

d

.

v

a

l

i

d

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

c

u

r

k

e

y

]

 

~

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

c

u

r

k

e

y

]

 

~

=

 

0

)

 

t

h

e

n




i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

c

u

r

k

e

y

]

 

=

=

 

a

d

d

:

G

e

t

I

D

(

)

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

I

t

e

m

 

"

 

.

.

 

a

d

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

 

a

d

d

e

d

 

t

o

 

Q

U

E

S

T

 

l

o

o

t

.

"

,

 

3

)

;




n

p

c

:

A

d

d

Q

u

e

s

t

L

o

o

t

(

a

d

d

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




t

r

a

d

e

_

r

e

t

u

r

n

[

"

i

t

e

m

"

 

.

.

 

a

]

 

=

 

n

i

l

;




f

o

u

n

d

i

t

e

m

 

=

 

t

r

u

e

;




a

c

c

e

p

t

e

d

 

=

 

t

r

u

e

;




i

t

e

m

i

d

 

=

 

0

;







i

f

(

t

e

x

t

 

~

=

 

n

i

l

 

o

r

 

e

m

o

t

e

 

~

=

 

n

i

l

)

 

t

h

e

n




r

e

q

u

i

r

e

d

_

i

t

e

m

s

 

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

i

t

e

m

s

 

-

 

1

;




i

f

(

r

e

q

u

i

r

e

d

_

i

t

e

m

s

 

~

=

 

0

)

 

t

h

e

n




i

f

(

t

e

x

t

 

~

=

 

n

i

l

)

 

t

h

e

n




n

p

c

:

S

a

y

(

"

"

 

.

.

 

t

e

x

t

 

.

.

 

"

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

m

o

t

e

 

~

=

 

n

i

l

)

 

t

h

e

n




n

p

c

:

E

m

o

t

e

(

"

"

 

.

.

 

e

m

o

t

e

 

.

.

 

"

"

)

;
















b

r

e

a

k

;




e

l

s

e




i

t

e

m

i

d

 

=

 

a

d

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

 

a

n

d

 

i

t

e

m

i

d

 

>

 

1

0

0

0

 

a

n

d

 

n

o

t

 

n

p

c

:

G

e

t

P

e

t

L

o

o

t

(

i

t

e

m

i

d

)

 

a

n

d

 

n

o

t

 

n

p

c

:

G

e

t

Q

u

e

s

t

L

o

o

t

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

I

t

e

m

 

"

 

.

.

 

i

t

e

m

i

d

 

.

.

 

"

 

a

d

d

e

d

 

t

o

 

P

E

T

 

l

o

o

t

.

"

,

 

3

)

;




n

p

c

:

A

d

d

P

e

t

L

o

o

t

(

i

t

e

m

i

d

)

;













i

f

(

n

o

t

 

f

o

u

n

d

i

t

e

m

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

"

c

o

p

p

e

r

"

]

 

=

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

"

s

i

l

v

e

r

"

]

 

=

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

"

g

o

l

d

"

]

 

=

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

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

]

 

=

=

 

n

i

l

)

 

t

h

e

n




i

f

(

a

c

c

e

p

t

e

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

"

N

P

C

 

w

a

s

 

h

a

n

d

e

d

 

a

n

 

i

t

e

m

 

i

t

 

d

o

e

s

n

'

t

 

n

e

e

d

,

 

b

u

t

 

a

l

s

o

 

r

e

c

e

i

v

e

d

 

v

a

l

i

d

 

i

t

e

m

s

.

"

,

 

3

)

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

o

r

 

i

 

=

 

1

,

 

4

 

d

o




l

o

c

a

l

 

k

e

y

 

=

 

"

i

t

e

m

"

 

.

.

 

i

;




i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

 

~

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

 

~

=

 

0

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

 

f

o

u

n

d

 

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

 

j

 

=

 

1

,

 

4

 

d

o







l

o

c

a

l

 

i

n

s

t

 

=

 

t

r

a

d

e

_

r

e

t

u

r

n

[

"

i

t

e

m

"

 

.

.

 

j

]

;




i

f

(

i

n

s

t

 

~

=

 

n

i

l

 

a

n

d

 

i

n

s

t

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

 

i

t

e

m

i

d

 

=

 

i

n

s

t

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

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

 

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




i

f

(

k

e

e

p

i

t

e

m

s

 

=

=

 

0

)

 

t

h

e

n




t

r

a

d

e

_

r

e

t

u

r

n

[

"

i

t

e

m

"

 

.

.

 

j

]

 

=

 

I

t

e

m

I

n

s

t

(

)

;







f

o

u

n

d

 

=

 

t

r

u

e

;







i

f

(

k

e

e

p

i

t

e

m

s

 

=

=

 

0

 

a

n

d

 

t

e

x

t

 

~

=

 

n

i

l

)

 

t

h

e

n




r

e

q

u

i

r

e

d

_

i

t

e

m

s

 

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

i

t

e

m

s

 

-

 

1

;




i

f

(

r

e

q

u

i

r

e

d

_

i

t

e

m

s

 

~

=

 

0

)

 

t

h

e

n




n

p

c

:

S

a

y

(

"

"

 

.

.

 

t

e

x

t

 

.

.

 

"

"

)

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




i

f

(

k

e

e

p

i

t

e

m

s

 

=

=

 

1

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

 

h

a

s

i

t

e

m

 

=

 

n

p

c

:

G

e

t

Q

u

e

s

t

L

o

o

t

(

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

)

;




i

f

(

h

a

s

i

t

e

m

)

 

t

h

e

n




f

o

u

n

d

 

=

 

t

r

u

e

;




e

l

s

e




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

A

n

 

i

t

e

m

 

t

h

e

 

N

P

C

 

r

e

q

u

i

r

e

s

 

(

"

 

.

.

 

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

 

.

.

 

"

)

 

w

a

s

 

n

o

t

 

h

a

n

d

e

d

 

t

o

 

t

h

e

m

 

a

n

d

 

i

s

 

n

o

t

 

i

n

 

t

h

e

i

r

 

l

o

o

t

.

"

,

 

3

)

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







e

l

s

e




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

(

N

o

n

-

M

Q

)

 

A

n

 

i

t

e

m

 

t

h

e

 

N

P

C

 

r

e

q

u

i

r

e

s

 

(

"

 

.

.

 

t

r

a

d

e

_

c

h

e

c

k

[

k

e

y

]

 

.

.

 

"

)

 

w

a

s

 

n

o

t

 

h

a

n

d

e

d

 

t

o

 

t

h

e

m

.

"

,

 

3

)

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






















l

o

c

a

l

 

i

t

e

m

1

 

=

 

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

1

"

]

;




l

o

c

a

l

 

i

t

e

m

2

 

=

 

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

2

"

]

;




l

o

c

a

l

 

i

t

e

m

3

 

=

 

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

3

"

]

;




l

o

c

a

l

 

i

t

e

m

4

 

=

 

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

4

"

]

;




i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

1

"

]

 

=

=

 

n

i

l

)

 

t

h

e

n




i

t

e

m

1

 

=

 

0

;







i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

2

"

]

 

=

=

 

n

i

l

)

 

t

h

e

n




i

t

e

m

2

 

=

 

0

;







i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

3

"

]

 

=

=

 

n

i

l

)

 

t

h

e

n




i

t

e

m

3

 

=

 

0

;







i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

"

i

t

e

m

4

"

]

 

=

=

 

n

i

l

)

 

t

h

e

n




i

t

e

m

4

 

=

 

0

;










i

f

(

k

e

e

p

i

t

e

m

s

 

=

=

 

1

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

 

c

o

u

n

t

 

=

 

n

p

c

:

H

a

s

R

e

q

u

i

r

e

d

Q

u

e

s

t

L

o

o

t

(

i

t

e

m

1

,

 

i

t

e

m

2

,

 

i

t

e

m

3

,

 

i

t

e

m

4

)

;




i

f

(

n

o

t

 

c

o

u

n

t

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

T

h

e

 

N

P

C

 

d

o

e

s

 

n

o

t

 

h

a

v

e

 

t

h

e

 

r

e

q

u

i

r

e

d

 

n

u

m

b

e

r

 

o

f

 

i

t

e

m

s

 

i

t

 

n

e

e

d

s

.

"

,

 

3

)

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
















l

o

c

a

l

 

t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

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

t

u

r

n

_

m

o

n

e

y

 

=

 

0

;







i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

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

]

 

~

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

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

]

 

~

=

 

0

)

 

t

h

e

n




t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

=

 

t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

+

 

(

t

r

a

d

e

_

c

h

e

c

k

[

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

]

 

*

 

1

0

0

0

)

;










i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

"

g

o

l

d

"

]

 

~

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

"

g

o

l

d

"

]

 

~

=

 

0

)

 

t

h

e

n




t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

=

 

t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

+

 

(

t

r

a

d

e

_

c

h

e

c

k

[

"

g

o

l

d

"

]

 

*

 

1

0

0

)

;










i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

"

s

i

l

v

e

r

"

]

 

~

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

"

s

i

l

v

e

r

"

]

 

~

=

 

0

)

 

t

h

e

n




t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

=

 

t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

+

 

(

t

r

a

d

e

_

c

h

e

c

k

[

"

s

i

l

v

e

r

"

]

 

*

 

1

0

)

;










i

f

(

t

r

a

d

e

_

c

h

e

c

k

[

"

c

o

p

p

e

r

"

]

 

~

=

 

n

i

l

 

a

n

d

 

t

r

a

d

e

_

c

h

e

c

k

[

"

c

o

p

p

e

r

"

]

 

~

=

 

0

)

 

t

h

e

n




t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

=

 

t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

 

+

 

t

r

a

d

e

_

c

h

e

c

k

[

"

c

o

p

p

e

r

"

]

;










r

e

t

u

r

n

_

m

o

n

e

y

 

=

 

r

e

t

u

r

n

_

m

o

n

e

y

 

+

 

t

r

a

d

e

_

r

e

t

u

r

n

[

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

]

 

*

 

1

0

0

0

 

+

 

t

r

a

d

e

_

r

e

t

u

r

n

[

"

g

o

l

d

"

]

 

*

 

1

0

0

;




r

e

t

u

r

n

_

m

o

n

e

y

 

=

 

r

e

t

u

r

n

_

m

o

n

e

y

 

+

 

t

r

a

d

e

_

r

e

t

u

r

n

[

"

s

i

l

v

e

r

"

]

 

*

 

1

0

 

+

 

t

r

a

d

e

_

r

e

t

u

r

n

[

"

c

o

p

p

e

r

"

]

;







i

f

(

r

e

t

u

r

n

_

m

o

n

e

y

 

<

 

t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

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




r

e

t

u

r

n

_

m

o

n

e

y

 

=

 

r

e

t

u

r

n

_

m

o

n

e

y

 

-

 

t

r

a

d

e

_

c

h

e

c

k

_

m

o

n

e

y

;













t

r

a

d

e

.

i

t

e

m

1

 

=

 

t

r

a

d

e

_

r

e

t

u

r

n

.

i

t

e

m

1

;




t

r

a

d

e

.

i

t

e

m

2

 

=

 

t

r

a

d

e

_

r

e

t

u

r

n

.

i

t

e

m

2

;




t

r

a

d

e

.

i

t

e

m

3

 

=

 

t

r

a

d

e

_

r

e

t

u

r

n

.

i

t

e

m

3

;




t

r

a

d

e

.

i

t

e

m

4

 

=

 

t

r

a

d

e

_

r

e

t

u

r

n

.

i

t

e

m

4

;







i

f

(

k

e

e

p

i

t

e

m

s

 

=

=

 

1

)

 

t

h

e

n




n

p

c

:

D

e

l

e

t

e

Q

u

e

s

t

L

o

o

t

(

i

t

e

m

1

,

 

i

t

e

m

2

,

 

i

t

e

m

3

,

 

i

t

e

m

4

)

;










t

r

a

d

e

.

p

l

a

t

i

n

u

m

 

=

 

m

a

t

h

.

f

l

o

o

r

(

r

e

t

u

r

n

_

m

o

n

e

y

 

/

 

1

0

0

0

)

;




r

e

t

u

r

n

_

m

o

n

e

y

 

=

 

r

e

t

u

r

n

_

m

o

n

e

y

 

-

 

(

t

r

a

d

e

.

p

l

a

t

i

n

u

m

 

*

 

1

0

0

0

)

;







t

r

a

d

e

.

g

o

l

d

 

=

 

m

a

t

h

.

f

l

o

o

r

(

r

e

t

u

r

n

_

m

o

n

e

y

 

/

 

1

0

0

)

;




r

e

t

u

r

n

_

m

o

n

e

y

 

=

 

r

e

t

u

r

n

_

m

o

n

e

y

 

-

 

(

t

r

a

d

e

.

g

o

l

d

 

*

 

1

0

0

)

;







t

r

a

d

e

.

s

i

l

v

e

r

 

=

 

m

a

t

h

.

f

l

o

o

r

(

r

e

t

u

r

n

_

m

o

n

e

y

 

/

 

1

0

)

;




r

e

t

u

r

n

_

m

o

n

e

y

 

=

 

r

e

t

u

r

n

_

m

o

n

e

y

 

-

 

(

t

r

a

d

e

.

s

i

l

v

e

r

 

*

 

1

0

)

;







t

r

a

d

e

.

c

o

p

p

e

r

 

=

 

r

e

t

u

r

n

_

m

o

n

e

y

;




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

T

h

e

 

q

u

e

s

t

 

c

o

m

p

l

e

t

e

d

 

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

.

"

,

3

)

;




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

u

n

c

t

i

o

n

 

i

t

e

m

s

.

r

e

t

u

r

n

_

i

t

e

m

s

(

n

p

c

,

 

c

l

i

e

n

t

,

 

t

r

a

d

e

,

 

t

e

x

t

)




i

f

 

(

 

t

y

p

e

(

t

e

x

t

)

 

=

=

 

"

b

o

o

l

e

a

n

"

 

a

n

d

 

t

e

x

t

 

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




t

e

x

t

 

=

 

"

"

;







l

o

c

a

l

 

r

e

t

u

r

n

e

d

 

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

 

i

 

=

 

1

,

 

4

 

d

o




l

o

c

a

l

 

i

n

s

t

 

=

 

t

r

a

d

e

[

"

i

t

e

m

"

 

.

.

 

i

]

;




i

f

(

i

n

s

t

 

~

=

 

n

i

l

 

a

n

d

 

i

n

s

t

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

 

i

t

e

m

i

d

 

=

 

i

n

s

t

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

n

o

t

 

n

p

c

:

G

e

t

Q

u

e

s

t

L

o

o

t

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




i

f

 

(

i

t

e

m

i

d

 

>

 

1

0

0

0

 

a

n

d

 

n

o

t

 

n

p

c

:

G

e

t

P

e

t

L

o

o

t

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

I

t

e

m

 

"

 

.

.

 

i

t

e

m

i

d

 

.

.

 

"

 

a

d

d

e

d

 

t

o

 

P

E

T

 

l

o

o

t

.

"

,

 

3

)

;




n

p

c

:

A

d

d

P

e

t

L

o

o

t

(

i

t

e

m

i

d

)

;







e

l

s

e







l

o

c

a

l

 

c

h

a

r

g

e

s

 

=

 

i

n

s

t

:

G

e

t

C

h

a

r

g

e

s

(

)

;




c

l

i

e

n

t

:

S

u

m

m

o

n

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

,

 

c

h

a

r

g

e

s

,

 

9

9

9

9

,

 

t

r

u

e

)

;




i

f

 

(

n

p

c

:

C

a

n

T

a

l

k

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

n

o

t

 

t

e

x

t

)

 

t

h

e

n




n

p

c

:

S

a

y

(

"

I

 

h

a

v

e

 

n

o

 

n

e

e

d

 

f

o

r

 

t

h

i

s

 

i

t

e

m

 

"

 

.

.

 

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

,

 

y

o

u

 

c

a

n

 

h

a

v

e

 

i

t

 

b

a

c

k

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

t

e

x

t

 

~

=

 

"

"

)

 

t

h

e

n




n

p

c

:

S

a

y

(

t

e

x

t

)

;










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

H

a

n

d

i

n

g

 

b

a

c

k

 

a

n

 

i

t

e

m

 

i

t

 

d

o

e

s

n

'

t

 

n

e

e

d

 

(

"

 

.

.

 

i

t

e

m

i

d

 

.

.

 

"

)

.

"

,

 

3

)

;




r

e

t

u

r

n

e

d

 

=

 

t

r

u

e

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

N

P

C

 

i

s

 

a

 

c

h

a

r

m

e

d

 

p

e

t

,

 

i

t

 

d

o

e

s

 

n

o

t

 

r

e

t

u

r

n

 

i

t

e

m

s

.

"

,

 

3

)

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

u

r

n

e

d

;










l

o

c

a

l

 

m

o

n

e

y

 

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

t

r

a

d

e

.

p

l

a

t

i

n

u

m

 

~

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

e

d

 

=

 

t

r

u

e

;




m

o

n

e

y

 

=

 

t

r

u

e

;










i

f

(

t

r

a

d

e

.

g

o

l

d

 

~

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

e

d

 

=

 

t

r

u

e

;




m

o

n

e

y

 

=

 

t

r

u

e

;










i

f

(

t

r

a

d

e

.

s

i

l

v

e

r

 

~

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

e

d

 

=

 

t

r

u

e

;




m

o

n

e

y

 

=

 

t

r

u

e

;










i

f

(

t

r

a

d

e

.

c

o

p

p

e

r

 

~

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

e

d

 

=

 

t

r

u

e

;




m

o

n

e

y

 

=

 

t

r

u

e

;










i

f

(

m

o

n

e

y

 

=

=

 

t

r

u

e

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

t

r

a

d

e

.

c

o

p

p

e

r

,

 

t

r

a

d

e

.

s

i

l

v

e

r

,

 

t

r

a

d

e

.

g

o

l

d

,

 

t

r

a

d

e

.

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










r

e

t

u

r

n

 

r

e

t

u

r

n

e

d

;










f

u

n

c

t

i

o

n

 

i

t

e

m

s

.

c

o

u

n

t

_

h

a

n

d

e

d

_

i

t

e

m

(

n

p

c

,

 

t

r

a

d

e

,

 

i

t

e

m

s

,

 

m

i

n

_

c

o

u

n

t

)







l

o

c

a

l

 

i

t

e

m

i

d

1

 

=

 

i

t

e

m

s

[

1

]

 

o

r

 

0

;




l

o

c

a

l

 

i

t

e

m

i

d

2

 

=

 

i

t

e

m

s

[

2

]

 

o

r

 

0

;




l

o

c

a

l

 

i

t

e

m

i

d

3

 

=

 

i

t

e

m

s

[

3

]

 

o

r

 

0

;




l

o

c

a

l

 

i

t

e

m

i

d

4

 

=

 

i

t

e

m

s

[

4

]

 

o

r

 

0

;




l

o

c

a

l

 

i

t

e

m

i

d

5

 

=

 

i

t

e

m

s

[

5

]

 

o

r

 

0

;




l

o

c

a

l

 

i

t

e

m

i

d

6

 

=

 

i

t

e

m

s

[

6

]

 

o

r

 

0

;




l

o

c

a

l

 

i

t

e

m

i

d

7

 

=

 

i

t

e

m

s

[

7

]

 

o

r

 

0

;




l

o

c

a

l

 

i

t

e

m

i

d

8

 

=

 

i

t

e

m

s

[

8

]

 

o

r

 

0

;




m

i

n

_

c

o

u

n

t

 

=

 

m

i

n

_

c

o

u

n

t

 

o

r

 

1

;







l

o

c

a

l

 

m

q

_

l

o

o

t

 

=

 

{

}

;







l

o

c

a

l

 

c

o

u

n

t

 

=

 

n

p

c

:

Q

u

e

s

t

L

o

o

t

C

o

u

n

t

(

i

t

e

m

i

d

1

)

 

+

 

n

p

c

:

Q

u

e

s

t

L

o

o

t

C

o

u

n

t

(

i

t

e

m

i

d

2

)

 

+

 

n

p

c

:

Q

u

e

s

t

L

o

o

t

C

o

u

n

t

(

i

t

e

m

i

d

3

)

 

+

 

n

p

c

:

Q

u

e

s

t

L

o

o

t

C

o

u

n

t

(

i

t

e

m

i

d

4

)

 

+




n

p

c

:

Q

u

e

s

t

L

o

o

t

C

o

u

n

t

(

i

t

e

m

i

d

5

)

 

+

 

n

p

c

:

Q

u

e

s

t

L

o

o

t

C

o

u

n

t

(

i

t

e

m

i

d

6

)

 

+

 

n

p

c

:

Q

u

e

s

t

L

o

o

t

C

o

u

n

t

(

i

t

e

m

i

d

7

)

 

+

 

n

p

c

:

Q

u

e

s

t

L

o

o

t

C

o

u

n

t

(

i

t

e

m

i

d

8

)

;




l

o

c

a

l

 

h

a

n

d

e

d

_

c

o

u

n

t

 

=

 

0

;




f

o

r

 

j

 

=

 

1

,

 

4

 

d

o




l

o

c

a

l

 

i

n

s

t

 

=

 

t

r

a

d

e

[

"

i

t

e

m

"

 

.

.

 

j

]

;




i

f

(

i

n

s

t

 

~

=

 

n

i

l

 

a

n

d

 

i

n

s

t

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

i

n

s

t

:

G

e

t

I

D

(

)

 

>

 

0

 

a

n

d

 

(

i

t

e

m

i

d

1

 

=

=

 

i

n

s

t

:

G

e

t

I

D

(

)

 

o

r

 

i

t

e

m

i

d

2

 

=

=

 

i

n

s

t

:

G

e

t

I

D

(

)

 

o

r

 

i

t

e

m

i

d

3

 

=

=

 

i

n

s

t

:

G

e

t

I

D

(

)

 

o

r

 

i

t

e

m

i

d

4

 

=

=

 

i

n

s

t

:

G

e

t

I

D

(

)

 

o

r




i

t

e

m

i

d

5

 

=

=

 

i

n

s

t

:

G

e

t

I

D

(

)

 

o

r

 

i

t

e

m

i

d

6

 

=

=

 

i

n

s

t

:

G

e

t

I

D

(

)

 

o

r

 

i

t

e

m

i

d

7

 

=

=

 

i

n

s

t

:

G

e

t

I

D

(

)

 

o

r

 

i

t

e

m

i

d

8

 

=

=

 

i

n

s

t

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

 

t

h

e

n




c

o

u

n

t

 

=

 

c

o

u

n

t

 

+

 

1

;




h

a

n

d

e

d

_

c

o

u

n

t

 

=

 

h

a

n

d

e

d

_

c

o

u

n

t

 

+

 

1

;




i

f

(

m

i

n

_

c

o

u

n

t

 

>

 

1

)

 

t

h

e

n







m

q

_

l

o

o

t

[

"

i

t

e

m

"

 

.

.

 

j

]

 

=

 

t

r

a

d

e

[

"

i

t

e

m

"

 

.

.

 

j

]

;







t

r

a

d

e

[

"

i

t

e

m

"

 

.

.

 

j

]

 

=

 

n

i

l

;




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

F

o

u

n

d

 

i

t

e

m

 

i

n

 

s

l

o

t

 

(

"

 

.

.

 

j

 

.

.

 

"

)

 

c

o

u

n

t

 

i

s

 

n

o

w

 

"

 

.

.

 

c

o

u

n

t

 

.

.

 

"

"

,

 

3

)

;
















i

f

(

h

a

n

d

e

d

_

c

o

u

n

t

 

=

=

 

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

Q

u

e

s

t

 

w

i

l

l

 

n

o

t

 

c

o

m

p

l

e

t

e

.

"

,

3

)

;




r

e

t

u

r

n

 

0

;










l

o

c

a

l

 

c

l

e

a

r

_

l

o

o

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

m

i

n

_

c

o

u

n

t

 

>

 

1

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

e

m

a

i

n

d

e

r

 

=

 

c

o

u

n

t

 

-

 

m

i

n

_

c

o

u

n

t

;




i

f

(

r

e

m

a

i

n

d

e

r

 

<

=

 

1

 

a

n

d

 

r

e

m

a

i

n

d

e

r

 

~

=

 

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

 

4

,

 

1

,

 

-

1

 

d

o




i

f

(

m

q

_

l

o

o

t

[

"

i

t

e

m

"

 

.

.

 

i

]

 

~

=

 

n

i

l

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

 

m

q

i

t

e

m

 

=

 

m

q

_

l

o

o

t

[

"

i

t

e

m

"

 

.

.

 

i

]

;




i

f

(

m

q

i

t

e

m

 

~

=

 

n

i

l

 

a

n

d

 

m

q

i

t

e

m

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




n

p

c

:

A

d

d

Q

u

e

s

t

L

o

o

t

(

m

q

i

t

e

m

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




c

l

e

a

r

_

l

o

o

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

r

e

m

a

i

n

d

e

r

 

=

=

 

1

)

 

t

h

e

n




b

r

e

a

k

;

























l

o

c

a

l

 

c

o

u

n

t

_

f

l

o

a

t

 

=

 

c

o

u

n

t

 

/

 

m

i

n

_

c

o

u

n

t

;




i

f

(

c

o

u

n

t

_

f

l

o

a

t

%

1

=

=

0

)

 

t

h

e

n




c

o

u

n

t

 

=

 

c

o

u

n

t

_

f

l

o

a

t

;




e

l

s

e




i

f

(

c

o

u

n

t

_

f

l

o

a

t

 

<

 

1

)

 

t

h

e

n




c

o

u

n

t

 

=

 

0

;




e

l

s

e




c

o

u

n

t

 

=

 

m

a

t

h

.

f

l

o

o

r

(

c

o

u

n

t

_

f

l

o

a

t

-

0

.

5

)

;
















i

f

(

c

l

e

a

r

_

l

o

o

t

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

C

l

e

a

r

i

n

g

 

q

u

e

s

t

 

l

o

o

t

"

,

 

3

)

;




n

p

c

:

D

e

l

e

t

e

Q

u

e

s

t

L

o

o

t

(

i

t

e

m

i

d

1

,

i

t

e

m

i

d

2

,

i

t

e

m

i

d

3

,

i

t

e

m

i

d

4

)

;




i

f

(

i

t

e

m

i

d

5

 

>

 

0

)

 

t

h

e

n




n

p

c

:

D

e

l

e

t

e

Q

u

e

s

t

L

o

o

t

(

i

t

e

m

i

d

5

,

i

t

e

m

i

d

6

,

i

t

e

m

i

d

7

,

i

t

e

m

i

d

8

)

;
















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

Q

u

e

s

t

 

w

i

l

l

 

c

o

m

p

l

e

t

e

 

"

 

.

.

 

c

o

u

n

t

 

.

.

 

"

 

t

i

m

e

s

.

"

,

 

3

)

;




r

e

t

u

r

n

 

c

o

u

n

t

;













r

e

t

u

r

n

 

i

t

e

m

s

;