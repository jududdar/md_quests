# Altunic Jartin

[Altunic Jartin](/npc/22069) is a level 20 Human Shopkeeper that spawns in [East Commonlands](/zone/22).

Their primary faction is [Knights of Truth](/faction/281).





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

R

u

n

n

i

n

g

(

t

r

u

e

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

R

u

n

n

i

n

g

(

f

a

l

s

e

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

A

l

t

u

n

i

c

 

J

a

r

t

i

n

 

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

,

 

t

r

a

v

e

l

e

r

!

 

H

a

v

e

 

y

o

u

 

n

e

e

d

 

o

f

 

p

r

o

v

i

s

i

o

n

s

 

o

r

 

p

e

r

h

a

p

s

 

o

t

h

e

r

 

w

a

r

e

s

?

 

I

 

s

e

l

l

 

w

h

a

t

 

I

 

f

i

n

d

 

u

p

o

n

 

t

h

e

 

b

a

t

t

l

e

g

r

o

u

n

d

s

 

o

f

 

t

h

e

 

C

o

m

m

o

n

l

a

n

d

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

W

h

e

r

e

 

i

s

 

y

o

u

r

 

h

o

u

s

e

`







i

f

 

*

*

F

a

c

t

i

o

n

*

*

 

>

=

 

A

m

i

a

b

l

e

 

t

h

e

n




>

*

*

A

l

t

u

n

i

c

 

J

a

r

t

i

n

 

s

a

y

s

:

*

*

 

F

o

l

l

o

w

 

m

e

.




e

q

.

m

o

v

e

_

t

o

(

4

7

9

1

.

0

6

,

-

8

3

.

5

5

,

-

5

1

.

4

7

)

;




*

*

S

p

a

w

n

 

N

P

C

:

*

*

 

 

[

S

q

u

i

r

e

 

N

a

r

l

]

(

/

n

p

c

/

2

2

1

9

6

)

 

a

t

 

(

*

*

y

:

*

*

 

-

1

0

5

.

4

9

,

 

*

*

x

:

*

*

 

4

7

0

7

.

6

3

)




e

l

s

e

i

f

 

*

*

F

a

c

t

i

o

n

*

*

 

>

=

 

I

n

d

i

f

f

e

r

e

n

t

 

t

h

e

n




>

*

*

A

l

t

u

n

i

c

 

J

a

r

t

i

n

 

s

a

y

s

:

*

*

 

W

o

r

k

 

o

n

 

t

h

e

 

w

a

y

s

 

o

f

 

v

a

l

o

r

 

b

e

f

o

r

e

 

w

e

 

d

i

s

c

u

s

s

 

s

u

c

h

 

t

h

i

n

g

s

.

 

Y

o

u

 

a

r

e

 

o

n

 

t

h

e

 

r

i

g

h

t

e

o

u

s

 

p

a

t

h

 

o

f

 

t

h

e

 

T

r

u

t

h

b

r

i

n

g

e

r

,

 

b

u

t

 

t

h

e

r

e

 

i

s

 

m

o

r

e

 

w

o

r

k

 

t

o

 

d

o

.




e

l

s

e




>

*

*

A

l

t

u

n

i

c

 

J

a

r

t

i

n

 

s

a

y

s

:

*

*

 

L

e

a

v

e

 

m

y

 

p

r

e

s

e

n

c

e

 

a

t

 

o

n

c

e

.

 

Y

o

u

r

 

w

a

y

s

 

o

f

 

l

i

f

e

 

a

r

e

 

n

o

t

 

a

c

c

e

p

t

a

b

l

e

 

t

o

 

o

n

e

 

w

h

o

 

f

o

l

l

o

w

s

 

t

h

e

 

T

r

u

t

h

b

r

i

n

g

e

r

.






















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

5

0

4

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

8

8

9

6

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

8

8

9

6

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

A

 

n

o

t

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

l

t

u

n

i

c

 

J

a

r

t

i

n

 

s

a

y

s

:

*

*

 

Y

o

u

 

a

r

e

 

t

h

e

 

o

n

e

 

t

h

e

y

 

h

a

v

e

 

s

e

n

t

?

 

A

 

s

q

u

i

r

e

?

!

!

 

I

 

h

o

p

e

 

y

o

u

 

c

a

n

 

h

e

l

p

 

m

e

.

 

I

 

g

a

t

h

e

r

 

i

t

e

m

s

 

s

t

r

e

w

n

 

u

p

o

n

 

t

h

e

 

g

r

o

u

n

d

s

 

o

f

 

t

h

e

 

C

o

m

m

o

n

l

a

n

d

s

.

 

I

 

s

e

l

l

 

t

h

e

m

 

a

t

 

g

o

o

d

 

p

r

i

c

e

s

.

 

L

a

t

e

l

y

,

 

I

 

h

a

v

e

 

b

e

e

n

 

t

e

r

r

o

r

i

z

e

d

 

b

y

 

a

 

h

u

m

a

n

 

r

o

g

u

e

 

n

a

m

e

d

 

N

a

r

l

.

 

H

e

 

w

i

l

l

 

n

o

 

d

o

u

b

t

 

a

p

p

e

a

r

 

a

t

 

m

y

 

[

h

o

u

s

e

]

 

s

o

o

n

.

 

B

r

i

n

g

 

h

i

s

 

h

e

a

d

 

t

o

 

m

e

.




e

l

s

e

i

f

(

 

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

9

8

2

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

3

8

6

7

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

3

8

6

7

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

A

 

H

u

m

a

n

 

H

e

a

d

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

l

t

u

n

i

c

 

J

a

r

t

i

n

 

s

a

y

s

:

*

*

 

Y

o

u

 

h

a

v

e

 

p

e

r

f

o

r

m

e

d

 

a

 

g

r

e

a

t

 

s

e

r

v

i

c

e

 

t

o

 

m

e

,

 

b

u

t

 

I

 

f

e

a

r

 

o

t

h

e

r

s

 

w

i

l

l

 

a

t

t

a

c

k

 

m

e

 

w

h

i

l

e

 

I

 

s

t

r

o

l

l

 

t

h

e

 

c

o

u

n

t

r

y

s

i

d

e

.

 

I

t

 

w

o

u

l

d

 

b

e

 

v

e

r

y

 

n

o

b

l

e

 

o

f

 

y

o

u

 

t

o

 

f

e

t

c

h

 

m

e

 

a

 

c

l

o

t

h

 

s

h

i

r

t

 

f

o

r

 

p

r

o

t

e

c

t

i

o

n

 

f

r

o

m

 

w

i

c

k

e

d

 

c

r

e

a

t

u

r

e

s

.

 

I

t

 

i

s

 

n

o

t

 

m

u

c

h

,

 

b

u

t

 

i

t

 

w

i

l

l

 

h

e

l

p

.




Y

o

u

r

 

f

a

c

t

i

o

n

 

s

t

a

n

d

i

n

g

 

w

i

t

h

 

[

K

n

i

g

h

t

s

 

o

f

 

T

r

u

t

h

]

(

/

f

a

c

t

i

o

n

/

2

8

1

)

 

g

o

t

 

b

e

t

t

e

r

 

(

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

'

t

e

x

t

-

s

u

c

c

e

s

s

'

>

+

5

<

/

s

p

a

n

>

)




Y

o

u

r

 

f

a

c

t

i

o

n

 

s

t

a

n

d

i

n

g

 

w

i

t

h

 

[

D

i

s

m

a

l

 

R

a

g

e

]

(

/

f

a

c

t

i

o

n

/

2

7

1

)

 

g

o

t

 

w

o

r

s

e

 

(

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

'

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

'

>

-

1

<

/

s

p

a

n

>

)




Y

o

u

r

 

f

a

c

t

i

o

n

 

s

t

a

n

d

i

n

g

 

w

i

t

h

 

[

T

h

e

 

F

r

e

e

p

o

r

t

 

M

i

l

i

t

i

a

]

(

/

f

a

c

t

i

o

n

/

3

3

0

)

 

g

o

t

 

w

o

r

s

e

 

(

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

'

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

'

>

-

1

<

/

s

p

a

n

>

)




Y

o

u

r

 

f

a

c

t

i

o

n

 

s

t

a

n

d

i

n

g

 

w

i

t

h

 

[

P

r

i

e

s

t

s

 

o

f

 

M

a

r

r

]

(

/

f

a

c

t

i

o

n

/

3

6

2

)

 

g

o

t

 

b

e

t

t

e

r

 

(

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

'

t

e

x

t

-

s

u

c

c

e

s

s

'

>

+

1

<

/

s

p

a

n

>

)




Y

o

u

r

 

f

a

c

t

i

o

n

 

s

t

a

n

d

i

n

g

 

w

i

t

h

 

[

S

t

e

e

l

 

W

a

r

r

i

o

r

s

]

(

/

f

a

c

t

i

o

n

/

3

1

1

)

 

g

o

t

 

b

e

t

t

e

r

 

(

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

'

t

e

x

t

-

s

u

c

c

e

s

s

'

>

+

1

<

/

s

p

a

n

>

)




 

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

 

N

o

 

i

t

e

m

 

g

i

v

e

n

 

(

+

5

0

0

 

e

x

p

)







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

 

c

o

i

n

:

*

*

 

0

 

<

i

m

g

 

s

r

c

=

'

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

6

4

4

.

p

n

g

'

 

w

i

d

t

h

=

'

1

4

'

 

h

e

i

g

h

t

=

'

1

4

'

/

>

 

0

 

<

i

m

g

 

s

r

c

=

'

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

6

4

5

.

p

n

g

'

 

w

i

d

t

h

=

'

1

4

'

 

h

e

i

g

h

t

=

'

1

4

'

/

>

 

0

 

<

i

m

g

 

s

r

c

=

'

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

6

4

6

.

p

n

g

'

 

w

i

d

t

h

=

'

1

4

'

 

h

e

i

g

h

t

=

'

1

4

'

/

>

 

1

-

1

0

 

<

i

m

g

 

s

r

c

=

'

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

6

4

7

.

p

n

g

'

 

w

i

d

t

h

=

'

1

4

'

 

h

e

i

g

h

t

=

'

1

4

'

/

>

 




e

l

s

e

i

f

(

 

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

6

7

8

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

0

0

4

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

0

0

4

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

C

l

o

t

h

 

S

h

i

r

t

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

l

t

u

n

i

c

 

J

a

r

t

i

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

a

n

k

 

y

o

u

.

 

Y

o

u

 

a

r

e

 

v

e

r

y

 

n

o

b

l

e

 

f

o

r

 

a

 

s

q

u

i

r

e

.

 

I

 

c

a

n

 

s

e

e

 

y

o

u

 

b

e

c

o

m

i

n

g

 

a

 

v

e

r

y

 

v

a

l

u

a

b

l

e

 

a

s

s

e

t

 

t

o

 

t

h

e

 

H

a

l

l

 

o

f

 

T

r

u

t

h

.

 

T

a

k

e

 

t

h

i

s

 

t

o

k

e

n

.

 

T

e

l

l

 

M

e

r

k

o

 

t

h

a

t

 

y

o

u

 

h

a

v

e

 

[

e

a

r

n

e

d

 

t

h

e

 

T

o

k

e

n

 

o

f

 

G

e

n

e

r

o

s

i

t

y

]

.




Y

o

u

r

 

f

a

c

t

i

o

n

 

s

t

a

n

d

i

n

g

 

w

i

t

h

 

[

K

n

i

g

h

t

s

 

o

f

 

T

r

u

t

h

]

(

/

f

a

c

t

i

o

n

/

2

8

1

)

 

g

o

t

 

b

e

t

t

e

r

 

(

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

'

t

e

x

t

-

s

u

c

c

e

s

s

'

>

+

5

<

/

s

p

a

n

>

)




Y

o

u

r

 

f

a

c

t

i

o

n

 

s

t

a

n

d

i

n

g

 

w

i

t

h

 

[

D

i

s

m

a

l

 

R

a

g

e

]

(

/

f

a

c

t

i

o

n

/

2

7

1

)

 

g

o

t

 

w

o

r

s

e

 

(

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

'

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

'

>

-

1

<

/

s

p

a

n

>

)




Y

o

u

r

 

f

a

c

t

i

o

n

 

s

t

a

n

d

i

n

g

 

w

i

t

h

 

[

T

h

e

 

F

r

e

e

p

o

r

t

 

M

i

l

i

t

i

a

]

(

/

f

a

c

t

i

o

n

/

3

3

0

)

 

g

o

t

 

w

o

r

s

e

 

(

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

'

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

'

>

-

1

<

/

s

p

a

n

>

)




Y

o

u

r

 

f

a

c

t

i

o

n

 

s

t

a

n

d

i

n

g

 

w

i

t

h

 

[

P

r

i

e

s

t

s

 

o

f

 

M

a

r

r

]

(

/

f

a

c

t

i

o

n

/

3

6

2

)

 

g

o

t

 

b

e

t

t

e

r

 

(

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

'

t

e

x

t

-

s

u

c

c

e

s

s

'

>

+

1

<

/

s

p

a

n

>

)




Y

o

u

r

 

f

a

c

t

i

o

n

 

s

t

a

n

d

i

n

g

 

w

i

t

h

 

[

S

t

e

e

l

 

W

a

r

r

i

o

r

s

]

(

/

f

a

c

t

i

o

n

/

3

1

1

)

 

g

o

t

 

b

e

t

t

e

r

 

(

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

'

t

e

x

t

-

s

u

c

c

e

s

s

'

>

+

1

<

/

s

p

a

n

>

)




 

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

6

4

6

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

3

8

6

5

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

3

8

6

5

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

o

k

e

n

 

o

f

 

G

e

n

e

r

o

s

i

t

y

<

/

a

>

 

(

+

5

0

0

 

e

x

p

)







 











