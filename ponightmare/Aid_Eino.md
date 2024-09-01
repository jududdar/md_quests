# Aid Eino

[Aid Eino](/npc/202122) is a level 60 Human Monk that spawns in [Plane of Nightmares](/zone/204).

Their primary faction is [Inhabitants of Tanaan](/faction/1636).l

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

 

D

R

E

A

M

K

E

E

P

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

4

8

0

;

 







l

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

M

A

N

_

S

P

A

W

N

P

O

I

N

T

I

D

 

=

 

3

4

5

8

5

6

;







l

o

c

a

l

 

e

s

c

o

r

t

D

o

n

e

 

=

 

f

a

l

s

e

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




>

*

A

i

d

 

E

i

n

o

 

s

t

e

p

s

 

f

r

o

m

 

t

h

e

 

s

h

a

d

o

w

s

 

'

I

 

a

m

 

g

l

a

d

 

y

o

u

 

w

e

r

e

 

a

b

l

e

 

t

o

 

c

o

m

e

 

h

e

l

p

 

m

e

,

 

t

h

i

s

 

i

s

 

q

u

i

t

e

 

a

 

d

a

n

g

e

r

o

u

s

 

r

e

a

l

m

!

 

 

W

e

 

m

u

s

t

 

t

r

e

a

d

 

c

a

r

e

f

u

l

l

y

 

i

f

 

w

e

 

a

r

e

 

t

o

 

f

i

n

d

 

t

h

e

 

i

t

e

m

 

K

e

r

a

s

h

a

 

d

e

s

i

r

e

s

 

f

r

o

m

 

t

h

i

s

 

v

i

l

e

 

p

l

a

c

e

.

 

 

S

o

m

e

t

i

m

e

s

 

I

 

w

o

r

r

y

 

h

e

r

 

r

e

s

e

a

r

c

h

 

w

i

t

h

 

t

h

e

 

m

a

g

i

c

 

o

f

 

t

h

e

 

l

a

n

d

 

p

u

t

s

 

h

e

r

 

i

n

 

m

u

c

h

 

d

a

n

g

e

r

.

 

 

L

e

t

 

u

s

 

b

e

 

o

f

f

 

a

n

d

 

f

i

n

d

 

t

h

a

t

 

w

h

i

c

h

 

s

h

e

 

d

e

s

i

r

e

s

.

'

*




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

e

t

r

e

s

p

a

w

n

*

 

f

o

r

 

1

 

s

e

c

o

n

d

s




e

s

c

o

r

t

D

o

n

e

 

=

 

f

a

l

s

e

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

s

e

t

r

e

s

p

a

w

n

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

e

t

r

e

s

p

a

w

n

*




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

I

N

V

I

S

_

M

A

N

_

S

P

A

W

N

P

O

I

N

T

I

D

)

:

S

e

t

T

i

m

e

r

(

2

1

6

0

0

0

0

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

d

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




*

*

A

i

d

 

E

i

n

o

 

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



















#

#

 

A

r

r

i

v

e

 

a

t

 

W

a

y

p

o

i

n

t

 

S

c

r

i

p

t







i

f

 

(

 

e

.

w

p

 

=

=

 

2

 

)

 

t

h

e

n




>

*

*

A

i

d

 

E

i

n

o

 

s

a

y

s

:

*

*

 

V

i

l

e

 

B

e

a

s

t

s

!

 

 

O

u

r

 

p

r

e

s

e

n

c

e

 

h

a

s

 

b

e

e

n

 

d

e

t

e

c

t

e

d

!

 

 

L

e

t

 

n

o

t

 

t

h

e

i

r

 

d

r

e

a

m

s

 

o

f

 

e

v

i

l

 

s

w

a

y

 

y

o

u

!




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

,

 

0

,

 

0

,

 

9

9

2

,

 

-

1

0

8

3

,

 

2

1

3

,

 

1

0

6

)

;




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

,

 

0

,

 

0

,

 

1

0

5

3

,

 

-

1

1

4

7

,

 

2

1

6

,

 

2

1

6

)

;




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

,

 

0

,

 

0

,

 

9

7

1

,

 

-

1

1

2

4

,

 

2

1

2

,

 

6

0

)

;




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

,

 

0

,

 

0

,

 

1

0

7

1

,

 

-

1

1

0

1

,

 

2

1

5

,

 

1

7

9

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

w

p

 

=

=

 

3

 

)

 

t

h

e

n




>

*

*

A

i

d

 

E

i

n

o

 

s

a

y

s

:

*

*

 

E

v

e

n

 

i

n

 

m

y

 

h

o

m

e

 

I

 

a

l

w

a

y

s

 

h

a

t

e

d

 

w

e

r

e

w

o

l

v

e

s

,

 

I

 

f

e

a

r

 

y

o

u

 

n

o

t

 

v

i

l

e

 

f

i

e

n

d

s

!




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

,

 

0

,

 

0

,

 

5

8

6

,

 

-

1

6

2

5

,

 

2

0

9

.

6

6

4

,

 

1

7

2

)

;




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

,

 

0

,

 

0

,

 

5

3

2

,

 

-

1

5

8

3

,

 

2

0

8

,

 

1

2

3

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

w

p

 

=

=

 

4

 

)

 

t

h

e

n




>

*

*

A

i

d

 

E

i

n

o

 

s

a

y

s

:

*

*

 

H

a

v

e

 

y

o

u

 

e

v

e

r

 

h

a

d

 

a

 

d

r

e

a

m

 

w

h

e

r

e

 

y

o

u

 

w

e

r

e

 

b

e

i

n

g

 

c

h

a

s

e

d

 

a

n

d

 

c

o

u

l

d

 

n

o

t

 

r

u

n

?

 

 

T

h

i

s

 

p

l

a

c

e

 

i

s

 

t

h

e

 

s

o

u

r

c

e

 

o

f

 

s

u

c

h

 

n

i

g

h

t

m

a

r

e

s

.

 

 

B

r

e

a

k

 

t

h

o

s

e

 

b

l

o

c

k

s

 

a

n

d

 

d

e

f

e

n

d

 

y

o

u

r

s

e

l

f

!




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

,

 

0

,

 

0

,

 

5

2

4

,

 

-

6

1

1

,

 

2

1

3

,

 

9

8

)

;




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

,

 

0

,

 

0

,

 

5

0

5

,

 

-

6

7

4

,

 

2

1

3

,

 

5

3

)

;




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

,

 

0

,

 

0

,

 

5

5

2

,

 

-

7

2

2

,

 

2

1

1

,

 

8

)

;




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

,

 

0

,

 

0

,

 

6

2

4

,

 

-

6

9

4

,

 

2

1

2

,

 

2

1

4

)

;




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

,

 

0

,

 

0

,

 

5

8

9

,

 

-

6

3

1

,

 

2

1

7

,

 

1

5

7

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

w

p

 

=

=

 

6

 

)

 

t

h

e

n




>

*

*

A

i

d

 

E

i

n

o

 

s

a

y

s

:

*

*

 

S

o

m

e

t

h

i

n

g

 

k

n

o

w

s

 

w

e

 

h

u

n

t

 

i

t

!

 

 

C

a

s

t

 

y

o

u

r

 

t

r

e

p

i

d

a

t

i

o

n

s

 

a

s

i

d

e

 

a

n

d

 

d

e

f

e

a

t

 

t

h

i

s

 

e

v

i

l

!

 

 

F

e

a

r

 

u

s

 

K

e

e

p

e

r

,

 

w

e

 

h

a

v

e

 

c

o

m

e

 

f

o

r

 

y

o

u

!




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

,

 

0

,

 

0

,

 

4

9

2

,

 

6

5

9

,

 

2

1

2

,

 

5

6

)

;




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

,

 

0

,

 

0

,

 

5

7

6

,

 

5

9

7

,

 

2

1

2

,

 

7

)

;




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

,

 

0

,

 

0

,

 

6

7

7

,

 

6

5

2

,

 

2

1

5

,

 

2

0

2

)

;




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

,

 

0

,

 

0

,

 

6

0

4

,

 

7

6

7

,

 

2

1

1

,

 

1

3

4

)

;




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

,

 

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

,

 

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

,

 

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

)

,

 

0

,

 

0

,

 

5

2

7

,

 

6

1

0

,

 

2

1

3

,

 

3

1

)

;




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

,

 

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

,

 

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

,

 

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

)

,

 

0

,

 

0

,

 

6

2

7

,

 

6

0

2

,

 

2

1

4

,

 

2

3

6

)

;




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

,

 

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

,

 

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

,

 

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

)

,

 

0

,

 

0

,

 

6

5

0

,

 

7

3

2

,

 

2

1

0

,

 

1

6

1

)

;




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

,

 

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

,

 

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

,

 

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

)

,

 

0

,

 

0

,

 

5

3

8

,

 

7

1

9

,

 

2

0

9

,

 

9

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

w

p

 

=

=

 

7

 

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

A

p

p

e

a

r

a

n

c

e

(

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

w

p

 

=

=

 

8

 

)

 

t

h

e

n




>

*

*

A

i

d

 

E

i

n

o

 

s

a

y

s

:

*

*

 

T

h

e

 

f

i

e

n

d

 

s

h

o

w

s

 

i

t

s

e

l

f

!

 

 

S

p

e

w

 

y

o

u

r

 

v

i

l

e

 

d

r

e

a

m

s

 

n

o

 

l

o

n

g

e

r

!

 

 

D

i

s

p

a

t

c

h

 

i

t

!




l

o

c

a

l

 

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

D

R

E

A

M

K

E

E

P

E

R

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

 

5

7

8

,

 

7

1

7

,

 

2

0

5

,

 

1

2

9

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

w

p

 

=

=

 

1

0

 

)

 

t

h

e

n




>

*

*

A

i

d

 

E

i

n

o

 

s

a

y

s

:

*

*

 

H

a

n

d

 

m

e

 

t

h

e

 

s

t

r

a

n

d

 

f

r

o

m

 

t

h

e

 

b

e

a

s

t

.

 

 

Q

u

e

l

l

i

o

u

s

 

k

n

o

w

s

 

w

h

a

t

 

K

e

r

a

s

h

a

 

w

a

n

t

s

 

w

i

t

h

 

s

u

c

h

 

a

 

t

h

i

n

g

.




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

d

e

p

o

p

*

 

f

o

r

 

1

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




e

s

c

o

r

t

D

o

n

e

 

=

 

t

r

u

e

;



















#

#

 

D

e

p

a

r

t

 

f

r

o

m

 

W

a

y

p

o

i

n

t

 

S

c

r

i

p

t




i

f

 

(

 

e

.

w

p

 

=

=

 

2

 

)

 

t

h

e

n




>

*

*

A

i

d

 

E

i

n

o

 

s

a

y

s

:

*

*

 

N

o

w

 

t

h

a

t

 

o

u

r

 

p

r

e

s

e

n

c

e

 

h

e

r

e

 

i

s

 

d

i

s

c

o

v

e

r

e

d

 

w

e

 

c

a

n

n

o

t

 

d

e

l

a

y

.

 

R

e

s

t

 

w

h

e

n

 

y

o

u

 

c

a

n

.




e

l

s

e

i

f

 

(

 

e

.

w

p

 

=

=

 

3

 

o

r

 

e

.

w

p

 

=

=

 

4

 

)

 

t

h

e

n




>

*

*

A

i

d

 

E

i

n

o

 

s

a

y

s

:

*

*

 

N

o

w

 

t

h

a

t

 

y

o

u

 

a

r

e

 

r

e

s

t

e

d

,

 

f

o

l

l

o

w

 

m

y

 

s

t

e

p

s

,

 

m

a

y

 

Q

u

e

l

l

i

o

u

s

 

g

u

a

r

d

 

u

s

!




e

l

s

e

i

f

 

(

 

e

.

w

p

 

=

=

 

6

 

)

 

t

h

e

n




>

*

*

A

i

d

 

E

i

n

o

 

s

a

y

s

:

*

*

 

E

x

c

e

l

l

e

n

t

 

r

e

s

t

 

u

p

 

f

o

r

 

a

 

f

e

w

 

m

o

m

e

n

t

s

,

 

r

a

l

l

y

 

y

o

u

r

 

s

t

r

e

n

g

t

h

 

a

s

 

I

 

m

e

d

i

t

a

t

e

 

o

n

 

a

 

t

e

a

c

h

i

n

g

 

o

f

 

Q

u

e

l

l

i

o

u

s

.




e

l

s

e

i

f

 

(

 

e

.

w

p

 

=

=

 

8

 

)

 

t

h

e

n




>

*

A

i

d

 

E

i

n

o

 

h

o

l

d

s

 

h

i

s

 

b

l

e

e

d

i

n

g

 

s

i

d

e

.

 

'

T

h

a

t

 

b

e

a

s

t

 

w

a

s

 

q

u

i

t

e

 

v

i

c

i

o

u

s

.

 

Q

u

i

c

k

l

y

!

 

L

e

t

 

u

s

 

m

a

k

e

 

o

u

r

 

w

a

y

 

t

o

 

t

h

e

 

p

o

r

t

a

l

.

 

I

 

m

u

s

t

 

s

e

e

k

 

t

h

e

 

h

e

a

l

e

r

s

 

o

f

 

t

r

a

n

q

u

i

l

i

t

y

 

t

o

 

s

t

a

n

c

h

 

t

h

e

 

b

l

e

e

d

i

n

g

 

o

f

 

t

h

i

s

 

w

o

u

n

d

.

 

 

G

i

v

e

 

m

e

 

a

 

m

o

m

e

n

t

 

t

o

 

g

a

t

h

e

r

 

m

y

 

s

t

r

e

n

g

t

h

.

'

*




e

l

s

e

i

f

 

(

 

e

.

w

p

 

=

=

 

9

 

)

 

t

h

e

n




>

*

A

i

d

 

E

i

n

o

 

g

a

t

h

e

r

s

 

h

i

s

 

s

t

r

e

n

g

t

h

 

a

n

d

 

l

i

m

p

s

 

f

o

r

w

a

r

d

.

 

'

F

o

l

l

o

w

 

m

y

 

s

t

e

p

s

 

t

o

 

t

h

e

 

p

o

r

t

a

l

!

'

*



















#

#

 

T

u

r

n

-

I

n

s










i

f

 

(

 

e

s

c

o

r

t

D

o

n

e

 

a

n

d

 

 

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

 

 

 

<

i

m

g

 

s

t

y

l

e

=

"

b

a

c

k

g

r

o

u

n

d

:

u

r

l

(

/

s

t

a

t

i

c

/

i

c

o

n

s

/

b

l

a

n

k

_

s

l

o

t

.

g

i

f

)

;

w

i

d

t

h

:

2

0

p

x

;

h

e

i

g

h

t

:

2

0

p

x

;

"

 

s

r

c

=

"

/

s

t

a

t

i

c

/

i

c

o

n

s

/

i

t

e

m

_

8

5

3

.

p

n

g

"

 

a

l

t

=

"

"

 

/

>

 

<

a




 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

h

r

e

f

=

"

/

i

t

e

m

/

1

6

2

6

1

"

 

d

a

t

a

-

u

r

l

=

"

1

6

2

6

1

"

 

c

l

a

s

s

=

"

t

o

o

l

t

i

p

-

l

i

n

k

 

l

i

n

k

"

>

S

t

r

a

n

d

 

o

f

 

N

i

g

h

t

m

a

r

e

<

/

a

>

 

 

)

 

t

h

e

n

 




>

*

*

A

i

d

 

E

i

n

o

 

s

a

y

s

:

*

*

 

E

x

c

e

l

l

e

n

t

!

 

 

Y

o

u

 

a

n

d

 

y

o

u

r

 

c

o

m

p

a

n

i

o

n

s

 

h

a

v

e

 

s

e

r

v

e

d

 

m

e

 

w

e

l

l

,

 

t

a

k

e

 

m

y

 

m

a

r

k

 

a

s

 

a

 

s

y

m

b

o

l

 

o

f

 

t

r

u

s

t

.

 

 

T

h

e

 

C

o

u

n

c

i

l

 

m

a

y

 

s

m

i

l

e

 

m

o

r

e

 

f

a

v

o

r

a

b

l

y

 

u

p

o

n

 

y

o

u

 

n

o

w

.

 

 

M

a

y

 

Q

u

e

l

l

i

o

u

s

 

w

a

t

c

h

 

o

v

e

r

 

y

o

u

!




 

&

#

1

2

7

8

7

3

;

 

*

*

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

:

*

*

 

 

<

i

m

g

 

s

t

y

l

e

=

"

b

a

c

k

g

r

o

u

n

d

:

u

r

l

(

/

s

t

a

t

i

c

/

i

c

o

n

s

/

b

l

a

n

k

_

s

l

o

t

.

g

i

f

)

;

w

i

d

t

h

:

2

0

p

x

;

h

e

i

g

h

t

:

2

0

p

x

;

"

 

s

r

c

=

"

/

s

t

a

t

i

c

/

i

c

o

n

s

/

i

t

e

m

_

9

7

1

.

p

n

g

"

 

a

l

t

=

"

"

 

/

>

 

<

a




 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

h

r

e

f

=

"

/

i

t

e

m

/

1

6

2

6

0

"

 

d

a

t

a

-

u

r

l

=

"

1

6

2

6

0

"

 

c

l

a

s

s

=

"

t

o

o

l

t

i

p

-

l

i

n

k

 

l

i

n

k

"

>

T

i

n

y

 

G

o

l

d

 

F

i

s

t

<

/

a

>

 

(

+

1

0

0

0

0

0

 

e

x

p

)







 




*

*

A

i

d

 

E

i

n

o

 

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










*

*

T

h

i

s

 

N

P

C

 

*

s

h

o

u

l

d

*

 

r

e

t

u

r

n

 

i

n

c

o

r

r

e

c

t

 

i

t

e

m

s

 

g

i

v

e

n

.

*

*




;


