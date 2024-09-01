# The Seventh Hammer

[The Seventh Hammer](/npc/201074) is a level 73 The Tribunal Monk that spawns in [Plane of Justice](/zone/201).l

o

c

a

l

 

I

N

V

I

S

_

T

R

I

B

U

N

A

L

_

T

Y

P

E

 

=

 

2

0

1

4

2

3

;

 




l

o

c

a

l

 

V

I

S

_

T

R

I

B

U

N

A

L

_

T

Y

P

E

 

=

 

2

0

1

4

2

7

;

 







l

o

c

a

l

 

s

k

i

p

A

g

g

r

o

T

e

x

t

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

n

i

m

a

t

e

T

r

i

b

u

n

a

l

(

a

n

i

m

a

t

i

o

n

I

d

)




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

 

a

n

d

 

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

 

=

=

 

V

I

S

_

T

R

I

B

U

N

A

L

_

T

Y

P

E

 

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

o

A

n

i

m

(

a

n

i

m

a

t

i

o

n

I

d

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




*

*

Y

o

u

 

s

a

y

:

*

*

 

`

h

a

i

l

`







>

*

*

T

h

e

 

S

e

v

e

n

t

h

 

H

a

m

m

e

r

 

s

a

y

s

:

*

*

 

G

r

e

e

t

i

n

g

s

 

m

o

r

t

a

l

,

 

i

t

 

s

e

e

m

s

 

t

h

e

 

c

o

u

n

c

i

l

 

h

a

s

 

d

e

e

m

e

d

 

y

o

u

 

w

o

r

t

h

y

 

o

f

 

t

h

e

 

c

h

a

l

l

e

n

g

e

,

 

a

r

e

 

y

o

u

 

r

e

a

d

y

 

t

o

 

f

a

c

e

 

j

u

d

g

e

m

e

n

t

?







*

*

Y

o

u

 

s

a

y

:

*

*

 

`

r

e

a

d

y

 

t

o

 

f

a

c

e

`







>

*

*

T

h

e

 

S

e

v

e

n

t

h

 

H

a

m

m

e

r

 

s

a

y

s

:

*

*

 

V

e

r

y

 

w

e

l

l

 

m

o

r

t

a

l

s

,

 

N

o

w

 

b

e

g

i

n

s

 

t

h

e

 

t

e

s

t

 

o

f

 

y

o

u

r

 

v

e

r

y

 

s

o

u

l

s

!




s

k

i

p

A

g

g

r

o

T

e

x

t

 

=

 

t

r

u

e

;




e

.

s

e

l

f

:

A

d

d

T

o

H

a

t

e

L

i

s

t

(

e

.

o

t

h

e

r

)

;



















#

#

 

C

o

m

b

a

t




i

f

 

 

T

h

e

 

S

e

v

e

n

t

h

 

H

a

m

m

e

r

 

e

n

t

e

r

s

 

c

o

m

b

a

t

 

 

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

 

s

k

i

p

A

g

g

r

o

T

e

x

t

 

)

 

t

h

e

n




>

*

*

T

h

e

 

S

e

v

e

n

t

h

 

H

a

m

m

e

r

 

s

a

y

s

:

*

*

 

P

r

e

p

a

r

e

 

f

o

r

 

j

u

d

g

e

m

e

n

t

 

m

o

r

t

a

l

s

!







e

q

.

s

e

t

_

t

i

m

e

r

(

"

v

e

r

d

i

c

t

"

,

 

m

a

t

h

.

r

a

n

d

o

m

(

1

8

1

,

 

1

9

0

)

 

*

 

1

0

0

0

)

;




e

q

.

s

e

t

_

t

i

m

e

r

(

"

t

r

e

m

o

r

"

,

 

m

a

t

h

.

r

a

n

d

o

m

(

8

6

,

 

9

5

)

 

*

 

1

0

0

0

)

;




*

*

S

t

o

p

 

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

s

t

o

p

*




e

l

s

e




s

k

i

p

A

g

g

r

o

T

e

x

t

 

=

 

f

a

l

s

e

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

s

t

o

p

*

 

f

o

r

 

6

0

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

v

e

r

d

i

c

t

"

 

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

v

e

r

d

i

c

t

*

 

f

o

r

 

1

8

7

 

s

e

c

o

n

d

s




A

n

i

m

a

t

e

T

r

i

b

u

n

a

l

(

4

2

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

G

e

t

M

o

b

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

I

N

V

I

S

_

T

R

I

B

U

N

A

L

_

T

Y

P

E

)

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

1

1

0

8

,

 

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

t

i

m

e

r

 

=

=

 

"

t

r

e

m

o

r

"

 

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

t

r

e

m

o

r

*

 

f

o

r

 

1

8

7

 

s

e

c

o

n

d

s




A

n

i

m

a

t

e

T

r

i

b

u

n

a

l

(

1

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

G

e

t

M

o

b

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

I

N

V

I

S

_

T

R

I

B

U

N

A

L

_

T

Y

P

E

)

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

1

1

0

7

,

 

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

t

i

m

e

r

 

=

=

 

"

s

t

o

p

"

 

)

 

t

h

e

n




*

*

S

t

o

p

 

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

s

t

o

p

*




*

*

S

t

o

p

 

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

v

e

r

d

i

c

t

*




*

*

S

t

o

p

 

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

r

e

m

o

r

*





