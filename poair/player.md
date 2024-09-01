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

 

1

 

a

n

d

 

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

 

2

8

6

3

8

 

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

1

5

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

6

1

7

,

 

5

,

 

1

4

5

0

,

 

6

4

)

;





