l

o

c

a

l

 

B

A

N

S

H

E

E

_

T

Y

P

E

 

=

 

2

0

4

0

1

5

;

 




l

o

c

a

l

 

N

I

G

H

T

S

T

A

L

K

E

R

_

T

Y

P

E

 

=

 

2

0

4

0

1

9

;

 




l

o

c

a

l

 

H

O

B

G

O

B

L

I

N

_

T

Y

P

E

 

=

 

2

0

4

0

1

1

;

 




l

o

c

a

l

 

T

R

E

M

U

L

O

U

S

_

B

A

T

_

T

Y

P

E

 

=

 

2

0

4

0

3

0

;

 




l

o

c

a

l

 

T

E

R

R

O

R

_

B

A

T

_

T

Y

P

E

 

=

 

2

0

4

0

4

2

;

 




l

o

c

a

l

 

T

O

R

M

E

N

T

_

B

A

T

_

T

Y

P

E

 

=

 

2

0

4

0

3

1

;

 







l

o

c

a

l

 

M

O

B

_

T

Y

P

E

S

 

=

 

{

 

[

B

A

N

S

H

E

E

_

T

Y

P

E

]

 

=

 

1

,

 

[

N

I

G

H

T

S

T

A

L

K

E

R

_

T

Y

P

E

]

 

=

 

1

,

 

[

H

O

B

G

O

B

L

I

N

_

T

Y

P

E

]

 

=

 

1

,

 

[

T

R

E

M

U

L

O

U

S

_

B

A

T

_

T

Y

P

E

]

 

=

 

1

,

 

[

T

E

R

R

O

R

_

B

A

T

_

T

Y

P

E

]

 

=

 

1

,

 

[

T

O

R

M

E

N

T

_

B

A

T

_

T

Y

P

E

]

 

=

 

1

 

}

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

E

i

n

o

I

n

v

i

s

D

a

y

 

s

p

a

w

n

"

,

 

2

)

;




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

t

i

m

e

c

h

e

c

k

*

 

f

o

r

 

1

0

 

s

e

c

o

n

d

s

























l

o

c

a

l

 

n

p

c

L

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

:

G

e

t

N

P

C

L

i

s

t

(

)

;







i

f

 

(

 

n

p

c

L

i

s

t

 

)

 

t

h

e

n




f

o

r

 

n

p

c

 

i

n

 

n

p

c

L

i

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




i

f

 

(

 

n

p

c

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

 

M

O

B

_

T

Y

P

E

S

[

n

p

c

:

G

e

t

N

P

C

T

y

p

e

I

D

(

)

]

 

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

G

e

t

X

(

)

 

>

 

4

8

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




n

p

c

:

D

e

p

o

p

(

)

;































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

t

i

m

e

c

h

e

c

k

"

 

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

 

z

o

n

e

T

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




i

f

 

(

 

z

o

n

e

T

i

m

e

 

>

 

1

9

 

o

r

 

z

o

n

e

T

i

m

e

 

<

 

7

 

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

E

i

n

o

I

n

v

i

s

D

a

y

 

d

e

s

p

a

w

n

"

,

 

2

)

;




*

*

E

i

n

o

I

n

v

i

s

D

a

y

 

d

e

s

p

a

w

n

s

.

*

*








