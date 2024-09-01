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

B

o

a

t

I

D

(

)

 

=

=

 

7

7

2

 

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

B

o

a

t

I

D

(

)

 

=

=

 

7

7

3

)

 

t

h

e

n




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

S

a

b

r

i

n

a

]

(

/

n

p

c

/

2

4

0

5

6

)




e

l

s

e




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

S

a

b

r

i

n

a

]

(

/

n

p

c

/

2

4

0

5

6

)



















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




e

.

s

e

l

f

:

S

e

t

B

o

a

t

I

D

(

7

7

2

)

;




e

.

s

e

l

f

:

S

e

t

B

o

a

t

N

a

m

e

(

"

S

e

a

_

K

i

n

g

0

0

0

"

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

S

e

t

t

i

n

g

 

b

o

a

t

 

t

o

 

S

e

a

_

K

i

n

g

0

0

0

 

f

o

r

 

p

l

a

y

e

r

 

a

t

 

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

G

e

t

X

(

)

 

.

.

 

"

,

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

G

e

t

Y

(

)

 

.

.

 

"

,

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

G

e

t

Z

(

)

 

.

.

 

"

"

,

 

1

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

s

i

g

n

a

l

 

=

=

 

2

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

S

e

t

B

o

a

t

I

D

(

7

7

3

)

;




e

.

s

e

l

f

:

S

e

t

B

o

a

t

N

a

m

e

(

"

G

o

l

d

e

n

_

M

a

i

d

e

n

0

0

0

"

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

S

e

t

t

i

n

g

 

b

o

a

t

 

t

o

 

G

o

l

d

e

n

_

M

a

i

d

e

n

0

0

0

 

f

o

r

 

p

l

a

y

e

r

 

a

t

 

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

G

e

t

X

(

)

 

.

.

 

"

,

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

G

e

t

Y

(

)

 

.

.

 

"

,

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

G

e

t

Z

(

)

 

.

.

 

"

"

,

 

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

 

e

v

e

n

t

_

b

o

a

r

d

_

b

o

a

t

(

e

)




l

o

c

a

l

 

z

o

n

e

_

t

i

m

e

 

=

 

e

q

.

g

e

t

_

z

o

n

e

_

t

i

m

e

(

)

;




l

o

c

a

l

 

h

o

u

r

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

h

o

u

r

"

]

;




l

o

c

a

l

 

m

i

n

u

t

e

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

m

i

n

u

t

e

"

]

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

 

A

t

:

 

"

 

.

.

 

h

o

u

r

 

.

.

 

"

:

"

 

.

.

 

m

i

n

u

t

e

 

.

.

 

"

 

B

o

a

t

I

D

:

 

"

 

.

.

 

e

.

b

o

a

t

_

i

d

 

.

.

 

"

 

w

a

s

 

b

o

a

r

d

e

d

.

 

I

t

s

 

n

a

m

e

 

i

s

:

 

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

G

e

t

B

o

a

t

N

a

m

e

(

)

 

.

.

 

"

.

"

,

 

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

 

e

v

e

n

t

_

l

e

a

v

e

_

b

o

a

t

(

e

)




l

o

c

a

l

 

z

o

n

e

_

t

i

m

e

 

=

 

e

q

.

g

e

t

_

z

o

n

e

_

t

i

m

e

(

)

;




l

o

c

a

l

 

h

o

u

r

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

h

o

u

r

"

]

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

 

A

t

:

 

"

 

.

.

 

h

o

u

r

 

.

.

 

"

:

0

0

 

I

 

l

e

f

t

 

B

o

a

t

I

D

:

 

"

 

.

.

 

e

.

b

o

a

t

_

i

d

 

.

.

 

"

.

"

,

 

1

)

;


