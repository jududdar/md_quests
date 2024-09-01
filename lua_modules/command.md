f

u

n

c

t

i

o

n

 

c

o

m

m

a

n

d

_

e

n

d

u

r

a

n

c

e

(

e

)




l

o

c

a

l

 

t

a

r

 

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

T

a

r

g

e

t

(

)

;




i

f

(

t

a

r

.

n

u

l

l

)

 

t

h

e

n




t

a

r

 

=

 

e

.

s

e

l

f

;










t

a

r

:

S

e

t

E

n

d

u

r

a

n

c

e

(

t

a

r

:

G

e

t

M

a

x

E

n

d

u

r

a

n

c

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

 

c

o

m

m

a

n

d

s

 

=

 

{

 

}

;




c

o

m

m

a

n

d

s

[

"

e

n

d

u

r

a

n

c

e

"

]

 

=

 

{

 

5

0

,

 

c

o

m

m

a

n

d

_

e

n

d

u

r

a

n

c

e

 

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

q

.

D

i

s

p

a

t

c

h

C

o

m

m

a

n

d

s

(

e

)




l

o

c

a

l

 

c

o

m

m

a

n

d

 

=

 

c

o

m

m

a

n

d

s

[

e

.

c

o

m

m

a

n

d

]

;




i

f

(

c

o

m

m

a

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

 

a

c

c

e

s

s

 

=

 

c

o

m

m

a

n

d

[

1

]

;




i

f

(

a

c

c

e

s

s

 

>

 

e

.

s

e

l

f

:

A

d

m

i

n

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

1

3

,

 

"

A

c

c

e

s

s

 

l

e

v

e

l

 

n

o

t

 

h

i

g

h

 

e

n

o

u

g

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

 

1

;










l

o

c

a

l

 

f

u

n

c

 

=

 

c

o

m

m

a

n

d

[

2

]

;




f

u

n

c

(

e

)

;




r

e

t

u

r

n

 

1

;







r

e

t

u

r

n

 

0

;


