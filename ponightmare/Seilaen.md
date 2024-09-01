# Seilaen

[Seilaen](/npc/204047) is a level 50 Human Druid that spawns in [Plane of Nightmares](/zone/204).l

o

c

a

l

 

D

E

Y

I

D

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

6

1

;

 







l

o

c

a

l

 

p

o

r

t

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




l

o

c

a

l

 

m

o

v

e

d

 

=

 

0

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

2

0

4

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




m

o

v

e

d

 

=

 

m

o

v

e

d

 

+

 

1

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

 

a

n

d

 

n

o

t

 

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
















r

e

t

u

r

n

 

m

o

v

e

d

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

2

0

4

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




m

o

v

e

d

 

=

 

m

o

v

e

d

 

+

 

1

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

 

a

n

d

 

n

o

t

 

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
















r

e

t

u

r

n

 

m

o

v

e

d

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

2

0

4

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

 

a

n

d

 

n

o

t

 

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










f

u

n

c

t

i

o

n

 

C

l

i

e

n

t

O

n

P

l

a

t

e

a

u

(

)




l

o

c

a

l

 

c

l

i

e

n

t

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

C

l

i

e

n

t

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

 

c

l

i

e

n

t

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

 

c

l

i

e

n

t

 

i

n

 

c

l

i

e

n

t

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

o

t

 

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

M

(

)




a

n

d

 

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

 

>

 

8

0

0

 

a

n

d

 

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

 

<

 

1

3

6

5




a

n

d

 

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

 

>

 

6

7

0

 

a

n

d

 

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

 

<

 

1

2

7

0




a

n

d

 

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

 

>

 

2

5

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

 

t

r

u

e

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

S

e

i

l

a

e

n

 

S

e

i

l

a

e

n

 

l

o

o

k

s

 

a

t

 

y

o

u

 

w

i

t

h

 

e

y

e

s

 

w

i

d

e

 

w

i

t

h

 

f

e

a

r

.

 

 

'

W

h

o

.

.

 

w

h

o

 

a

r

e

 

y

o

u

?

 

 

Y

o

u

.

.

 

Y

o

u

 

m

u

s

t

 

h

e

l

p

 

m

e

!

'

*







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

e

l

p

`







>

*

*

S

e

i

l

a

e

n

 

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

o

r

e

s

t

,

 

i

t

.

.

 

I

 

c

a

n

 

f

e

e

l

 

i

t

 

l

o

o

k

i

n

g

 

a

t

 

m

e

.

.

 

f

o

l

l

o

w

i

n

g

 

m

e

!

 

 

O

h

,

 

I

 

j

u

s

t

 

w

a

n

t

 

t

o

 

l

e

a

v

e

 

a

n

d

 

g

o

!







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

f

o

l

l

o

w

i

n

g

`







>

*

*

S

e

i

l

a

e

n

 

s

a

y

s

:

*

*

 

I

 

d

o

n

'

t

 

k

n

o

w

 

w

h

a

t

 

i

t

 

c

o

u

l

d

 

b

e

,

 

I

 

w

a

s

 

j

u

s

t

 

w

a

l

k

i

n

g

 

h

o

m

e

 

a

n

d

.

.

 

a

n

d

.

.

 

t

h

i

s

 

d

o

e

s

n

'

t

 

l

o

o

k

 

l

i

k

e

 

t

h

e

 

f

o

r

e

s

t

 

n

e

a

r

 

m

y

 

h

o

m

e

 

a

t

 

a

l

l

!

 

 

 

O

h

,

 

a

n

d

 

I

 

a

m

 

w

e

a

r

i

n

g

 

m

y

 

m

o

t

h

e

r

'

s

 

L

o

c

k

e

t

 

o

f

 

E

s

c

a

p

e

.

.

 

b

u

t

 

i

t

 

w

o

n

'

t

 

w

o

r

k

 

f

o

r

 

m

e

!







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

l

o

c

k

e

t

`







>

*

*

S

e

i

l

a

e

n

 

s

a

y

s

:

*

*

 

M

y

 

m

o

t

h

e

r

 

a

l

w

a

y

s

 

c

a

r

r

i

e

d

 

t

h

i

s

 

w

i

t

h

 

h

e

r

.

 

 

I

 

h

a

v

e

 

n

o

 

i

d

e

a

 

w

h

y

 

I

 

s

u

d

d

e

n

l

y

 

h

a

v

e

 

i

t

.

 

 

P

e

r

h

a

p

s

 

I

 

c

a

n

 

m

a

k

e

 

i

t

 

w

o

r

k

 

f

o

r

 

y

o

u

,

 

i

f

 

y

o

u

 

w

a

n

t

 

m

e

 

t

o

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

w

a

n

t

`










i

f

 

(

 

n

o

t

 

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

I

s

M

o

b

S

p

a

w

n

e

d

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

D

E

Y

I

D

_

T

Y

P

E

)

 

)

 

t

h

e

n




>

*

*

S

e

i

l

a

e

n

 

s

a

y

s

:

*

*

 

O

h

 

i

t

 

w

o

r

k

e

d

!

 

 

A

r

e

 

y

o

u

 

s

t

i

l

l

 

h

e

r

e

?

 

 

O

h

,

 

p

l

e

a

s

e

,

 

d

o

n

'

t

 

h

a

v

e

 

l

e

f

t

 

m

e

.

 

 

C

o

m

e

 

t

e

l

l

 

m

e

 

y

o

u

 

a

r

e

 

s

t

i

l

l

 

h

e

r

e

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

D

E

Y

I

D

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

1

1

,

 

1

0

8

1

,

 

2

8

3

.

4

6

2

,

 

5

9

)

;




e

.

o

t

h

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

2

0

4

,

 

1

2

1

3

,

 

1

1

0

3

,

 

2

8

2

,

 

1

8

7

*

2

)

;




e

l

s

e




>

*

*

S

e

i

l

a

e

n

 

s

a

y

s

:

*

*

 

H

m

m

.

.

 

I

t

 

d

o

e

s

n

'

t

 

s

e

e

m

 

t

o

 

w

a

n

t

 

t

o

 

w

o

r

k

.

 

 

D

o

 

y

o

u

 

s

e

e

 

D

e

y

i

d

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

w

h

e

r

e

`







>

*

*

S

e

i

l

a

e

n

 

s

a

y

s

:

*

*

 

W

h

a

t

 

d

i

d

 

y

o

u

 

s

e

e

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

d

e

y

i

d

`







>

*

*

S

e

i

l

a

e

n

 

s

a

y

s

:

*

*

 

O

h

h

,

 

t

h

a

t

 

m

u

s

t

 

b

e

 

w

h

a

t

 

i

s

 

c

a

u

s

i

n

g

 

a

l

l

 

t

h

i

s

 

t

r

o

u

b

l

e

!

 

 

Y

o

u

 

a

l

l

 

s

e

e

m

 

s

o

 

b

r

a

v

e

.

 

 

M

a

y

b

e

 

i

f

 

y

o

u

 

c

h

o

p

 

d

o

w

n

 

D

e

y

i

d

 

t

h

e

 

T

w

i

s

t

e

d

 

I

 

w

i

l

l

 

b

e

 

a

b

l

e

 

t

o

 

g

o

 

h

o

m

e

?

 

 

W

i

l

l

 

y

o

u

 

p

l

e

a

s

e

?

 

 

I

f

 

y

o

u

 

h

a

v

e

 

g

a

t

h

e

r

e

d

 

t

o

g

e

t

h

e

r

 

a

n

d

 

a

r

e

 

p

r

e

p

a

r

e

d

,

 

h

a

v

e

 

y

o

u

r

 

l

e

a

d

e

r

s

 

s

t

e

p

 

f

o

r

w

a

r

d

 

a

n

d

 

t

e

l

l

 

m

e

 

t

h

e

i

r

 

r

e

a

d

i

n

e

s

s

.

 

 

M

o

t

h

e

r

'

s

 

L

o

c

k

e

t

 

d

o

e

s

n

'

t

 

s

e

e

m

 

a

s

 

b

r

i

g

h

t

 

a

s

 

i

t

 

w

a

s

 

b

e

f

o

r

e

.

 

 

I

 

f

e

a

r

 

I

 

c

a

n

 

o

n

l

y

 

u

s

e

 

i

t

 

b

u

t

 

a

 

c

o

u

p

l

e

 

m

o

r

e

 

t

i

m

e

s

.







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

`










i

f

 

(

 

p

o

r

t

s

 

<

 

2

 

)

 

t

h

e

n







p

o

r

t

s

 

=

 

p

o

r

t

s

 

+

 

1

;




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

e

.

o

t

h

e

r

,

 

1

5

0

,

 

1

2

1

3

,

 

1

1

0

3

,

 

2

8

2

,

 

1

8

7

)

;




e

l

s

e




>

*

*

S

e

i

l

a

e

n

 

s

a

y

s

:

*

*

 

O

h

,

 

I

 

a

m

 

s

o

r

r

y

 

I

 

c

a

n

'

t

 

m

a

k

e

 

i

t

 

w

o

r

k

 

a

n

y

 

m

o

r

e

!

 

 

I

 

d

o

 

h

o

p

e

 

t

h

o

s

e

 

t

h

a

t

 

a

r

e

 

u

p

 

o

n

 

t

h

e

 

p

l

a

t

e

a

u

 

w

i

l

l

 

b

e

 

s

u

f

f

i

c

i

e

n

t

 

t

o

 

o

v

e

r

c

o

m

e

 

t

h

e

 

b

i

g

 

t

r

e

e

!






















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




*

*

S

e

i

l

a

e

n

 

s

h

o

u

t

s

:

*

*

 

<

s

p

a

n

 

c

l

a

s

s

=

"

t

e

x

t

-

d

a

n

g

e

r

"

>

O

h

 

t

h

a

n

k

 

y

o

u

!

 

T

h

a

n

k

 

y

o

u

!

 

I

 

d

o

n

'

t

 

f

e

e

l

 

t

h

e

 

t

r

e

e

s

 

w

a

t

c

h

i

n

g

 

m

e

 

a

n

y

m

o

r

e

!

 

 

A

n

d

.

.

 

L

e

t

 

m

e

 

t

r

y

 

M

o

t

h

e

r

'

s

 

L

o

c

k

e

t

 

a

g

a

i

n

,

 

I

 

t

h

i

n

k

 

i

t

 

m

i

g

h

t

 

w

o

r

k

.

.

<

/

s

p

a

n

>




*

*

S

e

i

l

a

e

n

 

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




i

f

 

(

 

n

o

t

 

C

l

i

e

n

t

O

n

P

l

a

t

e

a

u

(

)

 

)

 

t

h

e

n




p

o

r

t

s

 

=

 

0

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

D

e

y

i

d

 

e

v

e

n

t

 

r

e

s

e

t

"

,

 

1

)

;




e

l

s

e




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

c

h

e

c

k

p

l

a

t

e

a

u

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




p

o

r

t

s

 

=

 

0

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

c

h

e

c

k

p

l

a

t

e

a

u

"

 

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

 

C

l

i

e

n

t

O

n

P

l

a

t

e

a

u

(

)

 

)

 

t

h

e

n




p

o

r

t

s

 

=

 

0

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

c

h

e

c

k

p

l

a

t

e

a

u

*




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

D

e

y

i

d

 

e

v

e

n

t

 

r

e

s

e

t

"

,

 

1

)

;








