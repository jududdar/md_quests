l

o

c

a

l

 

T

M

 

=

 

{

 

}

;




l

o

c

a

l

 

T

h

r

e

a

d

M

a

n

a

g

e

r

 

=

 

{

 

S

t

a

t

e

F

i

r

s

t

R

u

n

 

=

 

0

,

 

S

t

a

t

e

R

u

n

n

i

n

g

 

=

 

1

,

 

S

t

a

t

e

S

u

s

p

e

n

d

e

d

 

=

 

2

,

 

S

t

a

t

e

W

a

i

t

i

n

g

 

=

 

3

,

 

t

h

r

e

a

d

s

 

=

 

{

 

}

 

}




s

e

t

m

e

t

a

t

a

b

l

e

(

T

h

r

e

a

d

M

a

n

a

g

e

r

,

 

{

 

_

_

i

n

d

e

x

 

=

 

T

M

 

}

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

 

T

h

r

e

a

d

M

a

n

a

g

e

r

:

R

e

s

u

m

e

(

n

a

m

e

)




f

o

r

 

i

 

=

 

1

,

 

#

s

e

l

f

.

t

h

r

e

a

d

s

 

d

o




i

f

(

s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

n

a

m

e

 

=

=

 

n

a

m

e

)

 

t

h

e

n




i

f

(

s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

s

t

a

t

e

 

=

=

 

s

e

l

f

.

S

t

a

t

e

F

i

r

s

t

R

u

n

)

 

t

h

e

n




s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

s

t

a

t

e

 

=

 

s

e

l

f

.

S

t

a

t

e

R

u

n

n

i

n

g

;




c

o

r

o

u

t

i

n

e

.

r

e

s

u

m

e

(

s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

c

o

,

 

u

n

p

a

c

k

(

s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

a

r

g

s

)

)

;




e

l

s

e

i

f

(

s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

s

t

a

t

e

 

=

=

 

s

e

l

f

.

S

t

a

t

e

S

u

s

p

e

n

d

e

d

)

 

t

h

e

n




s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

s

t

a

t

e

 

=

 

s

e

l

f

.

S

t

a

t

e

R

u

n

n

i

n

g

;




c

o

r

o

u

t

i

n

e

.

r

e

s

u

m

e

(

s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

c

o

)

;




e

l

s

e

i

f

(

s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

s

t

a

t

e

 

=

=

 

s

e

l

f

.

S

t

a

t

e

W

a

i

t

i

n

g

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

c

l

o

c

k

(

)

 

>

=

 

s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

w

a

i

t

_

u

n

t

i

l

)

 

t

h

e

n




s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

s

t

a

t

e

 

=

 

s

e

l

f

.

S

t

a

t

e

R

u

n

n

i

n

g

;




c

o

r

o

u

t

i

n

e

.

r

e

s

u

m

e

(

s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

c

o

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

 

T

h

r

e

a

d

M

a

n

a

g

e

r

:

C

r

e

a

t

e

(

n

a

m

e

,

 

f

,

 

.

.

.

)




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

s

e

l

f

.

t

h

r

e

a

d

s

,

 

{




_

n

a

m

e

 

=

 

n

a

m

e

,




_

c

o

 

=

 

c

o

r

o

u

t

i

n

e

.

c

r

e

a

t

e

(

f

)

,




_

a

r

g

s

 

=

 

{

.

.

.

}

,




_

s

t

a

t

e

 

=

 

s

e

l

f

.

S

t

a

t

e

F

i

r

s

t

R

u

n

,




_

w

a

i

t

_

u

n

t

i

l

 

=

 

0

.

0




}

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

 

T

h

r

e

a

d

M

a

n

a

g

e

r

:

Y

i

e

l

d

(

.

.

.

)




l

o

c

a

l

 

r

u

n

n

i

n

g

 

=

 

c

o

r

o

u

t

i

n

e

.

r

u

n

n

i

n

g

(

)

;




i

f

(

r

u

n

n

i

n

g

 

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




r

e

t

u

r

n

;










f

o

r

 

i

 

=

 

1

,

 

#

s

e

l

f

.

t

h

r

e

a

d

s

 

d

o




i

f

(

s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

c

o

 

=

=

 

r

u

n

n

i

n

g

)

 

t

h

e

n




s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

s

t

a

t

e

 

=

 

s

e

l

f

.

S

t

a

t

e

S

u

s

p

e

n

d

e

d

;




c

o

r

o

u

t

i

n

e

.

y

i

e

l

d

(

.

.

.

)

;




r

e

t

u

r

n

;













c

o

r

o

u

t

i

n

e

.

y

i

e

l

d

(

.

.

.

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

 

T

h

r

e

a

d

M

a

n

a

g

e

r

:

W

a

i

t

(

t

,

 

.

.

.

)




l

o

c

a

l

 

r

u

n

n

i

n

g

 

=

 

c

o

r

o

u

t

i

n

e

.

r

u

n

n

i

n

g

(

)

;




i

f

(

r

u

n

n

i

n

g

 

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




r

e

t

u

r

n

;










f

o

r

 

i

 

=

 

1

,

 

#

s

e

l

f

.

t

h

r

e

a

d

s

 

d

o




i

f

(

s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

c

o

 

=

=

 

r

u

n

n

i

n

g

)

 

t

h

e

n




s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

s

t

a

t

e

 

=

 

s

e

l

f

.

S

t

a

t

e

W

a

i

t

i

n

g

;




s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

w

a

i

t

_

u

n

t

i

l

 

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

 

+

 

t

;




c

o

r

o

u

t

i

n

e

.

y

i

e

l

d

(

.

.

.

)

;




r

e

t

u

r

n

;













c

o

r

o

u

t

i

n

e

.

y

i

e

l

d

(

.

.

.

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

 

T

h

r

e

a

d

M

a

n

a

g

e

r

:

S

t

o

p

(

)




l

o

c

a

l

 

r

u

n

n

i

n

g

 

=

 

c

o

r

o

u

t

i

n

e

.

r

u

n

n

i

n

g

(

)

;




i

f

(

r

u

n

n

i

n

g

 

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




r

e

t

u

r

n

;










f

o

r

 

i

 

=

 

1

,

 

#

s

e

l

f

.

t

h

r

e

a

d

s

 

d

o




i

f

(

s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

c

o

 

=

=

 

r

u

n

n

i

n

g

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

s

e

l

f

.

t

h

r

e

a

d

s

,

 

i

)

;




c

o

r

o

u

t

i

n

e

.

y

i

e

l

d

(

)

;




r

e

t

u

r

n

;













c

o

r

o

u

t

i

n

e

.

y

i

e

l

d

(

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

 

T

h

r

e

a

d

M

a

n

a

g

e

r

:

C

l

e

a

r

(

)




l

o

c

a

l

 

r

u

n

n

i

n

g

 

=

 

c

o

r

o

u

t

i

n

e

.

r

u

n

n

i

n

g

(

)

;




s

e

l

f

.

t

h

r

e

a

d

s

 

=

 

{

 

}

;




i

f

(

r

u

n

n

i

n

g

)

 

t

h

e

n




c

o

r

o

u

t

i

n

e

.

y

i

e

l

d

(

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

 

T

h

r

e

a

d

M

a

n

a

g

e

r

:

G

a

r

b

a

g

e

C

o

l

l

e

c

t

(

)




i

f

(

#

s

e

l

f

.

t

h

r

e

a

d

s

 

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










f

o

r

 

i

 

=

 

#

s

e

l

f

.

t

h

r

e

a

d

s

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

c

o

r

o

u

t

i

n

e

.

s

t

a

t

u

s

(

s

e

l

f

.

t

h

r

e

a

d

s

[

i

]

.

_

c

o

)

 

=

=

 

"

d

e

a

d

"

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

s

e

l

f

.

t

h

r

e

a

d

s

,

 

i

)

;
















r

e

t

u

r

n

 

T

h

r

e

a

d

M

a

n

a

g

e

r

;