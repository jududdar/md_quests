# Farkus Grime

[Farkus Grime](/npc/181164) is a level 25 Human Shadow Knight that spawns in [Jaggedpine Forest](/zone/181).





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




t

e

l

l

p

a

u

s

e

 

=

 

0

;




a

l

r

e

a

d

y

_

t

e

l

l

 

=

 

0

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

F

a

r

k

u

s

 

G

r

i

m

e

 

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

?

 

W

h

a

t

 

d

o

 

y

o

u

 

w

a

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

d

i

s

e

a

s

e

d

 

b

e

a

r

 

l

i

v

e

r

`







>

*

F

a

r

k

u

s

 

G

r

i

m

e

 

c

l

e

n

c

h

e

s

 

h

i

s

 

t

e

e

t

h

 

a

n

d

 

s

p

e

a

k

s

 

i

n

 

a

 

q

u

i

e

t

 

b

u

t

 

d

e

a

d

l

y

 

t

o

n

e

,

 

'

K

e

e

p

 

y

o

u

r

 

v

o

i

c

e

 

d

o

w

n

 

y

o

u

 

f

o

o

l

,

 

m

e

n

t

i

o

n

 

o

f

 

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

 

a

r

o

u

n

d

 

h

e

r

e

 

i

s

 

d

a

n

g

e

r

o

u

s

!

 

I

'

m

 

a

l

w

a

y

s

 

w

i

l

l

i

n

g

 

t

o

 

h

e

l

p

 

s

o

m

e

o

n

e

 

w

h

o

 

s

h

a

r

e

s

 

t

h

e

 

s

a

m

e

.

.

.

 

p

h

i

l

o

s

o

p

h

y

.

.

.

 

a

s

 

m

y

s

e

l

f

 

t

h

o

u

g

h

.

 

A

r

e

 

y

o

u

 

[

t

r

u

l

y

 

s

e

r

i

o

u

s

]

 

a

b

o

u

t

 

t

h

i

s

?

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

t

r

u

l

y

 

s

e

r

i

o

u

s

`







>

*

*

F

a

r

k

u

s

 

G

r

i

m

e

 

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

,

 

f

o

l

l

o

w

 

m

e

 

a

n

d

 

w

e

'

l

l

 

h

a

v

e

 

a

 

l

i

t

t

l

e

 

c

h

a

t

 

t

h

e

n

.




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

X

(

)

 

=

=

 

1

8

3

0

 

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

Y

(

)

 

=

=

 

1

3

1

6

)

 

t

h

e

n




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

1

3

9

0

,

1

3

6

0

,

1

9

,

0

,

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

 

=

=

 

1

3

9

0

 

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

Y

(

)

 

=

=

 

1

3

6

0

 

a

n

d

 

a

l

r

e

a

d

y

_

t

e

l

l

 

=

=

 

0

)

 

t

h

e

n




a

l

r

e

a

d

y

_

t

e

l

l

 

=

 

1

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

S

e

c

r

e

t

s

*

 

f

o

r

 

2

 

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

S

e

c

r

e

t

s

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

S

e

c

r

e

t

s

*

 

f

o

r

 

7

 

s

e

c

o

n

d

s




t

e

l

l

p

a

u

s

e

 

=

 

t

e

l

l

p

a

u

s

e

 

+

 

1

;




i

f

(

t

e

l

l

p

a

u

s

e

 

=

=

 

1

)

 

t

h

e

n




>

*

*

F

a

r

k

u

s

 

G

r

i

m

e

 

s

a

y

s

:

*

*

 

I

 

h

a

d

 

n

o

t

 

p

e

g

g

e

d

 

y

o

u

 

a

s

 

o

n

e

 

a

l

l

i

e

d

 

w

i

t

h

 

t

h

e

 

P

l

a

g

u

e

b

r

i

n

g

e

r

,

 

m

a

y

 

h

i

s

 

b

l

e

s

s

i

n

g

 

o

n

c

e

 

a

g

a

i

n

 

s

p

r

e

a

d

 

a

c

r

o

s

s

 

t

h

e

 

l

a

n

d

.




e

l

s

e

i

f

(

t

e

l

l

p

a

u

s

e

 

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

F

a

r

k

u

s

 

G

r

i

m

e

 

s

a

y

s

:

*

*

 

S

o

 

y

o

u

 

w

i

s

h

 

f

o

r

 

m

e

 

t

o

 

d

e

f

i

l

e

 

o

n

e

 

o

f

 

t

h

e

s

e

 

s

o

-

c

a

l

l

e

d

 

'

s

a

c

r

e

d

'

 

b

e

a

r

s

 

f

o

r

 

y

o

u

?

 

I

'

m

 

n

o

t

 

s

u

r

e

 

w

h

a

t

 

v

i

l

e

 

r

i

t

u

a

l

 

y

o

u

 

w

o

u

l

d

 

n

e

e

d

 

t

h

i

s

 

l

i

v

e

r

 

f

o

r

 

b

u

t

 

I

'

d

 

b

e

 

d

e

l

i

g

h

t

e

d

 

t

o

 

a

s

s

i

s

t

 

y

o

u

.




e

l

s

e

i

f

(

t

e

l

l

p

a

u

s

e

 

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

F

a

r

k

u

s

 

G

r

i

m

e

 

s

a

y

s

:

*

*

 

H

o

w

e

v

e

r

,

 

b

e

f

o

r

e

 

I

 

d

o

 

t

h

i

s

 

t

h

i

n

g

 

f

o

r

 

y

o

u

 

t

h

e

r

e

'

s

 

s

o

m

e

t

h

i

n

g

 

I

 

n

e

e

d

 

f

o

r

 

y

o

u

 

t

o

 

d

o

 

f

o

r

 

m

e

 

t

o

 

s

h

o

w

 

y

o

u

r

 

l

o

y

a

l

t

y

.

 

A

n

d

 

t

o

 

h

e

l

p

 

m

e

 

t

o

 

s

e

t

t

l

e

 

a

n

 

o

u

t

s

t

a

n

d

i

n

g

 

s

c

o

r

e

 

o

f

 

c

o

u

r

s

e

.




e

l

s

e

i

f

(

t

e

l

l

p

a

u

s

e

 

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

F

a

r

k

u

s

 

G

r

i

m

e

 

s

a

y

s

:

*

*

 

I

 

w

a

n

t

 

y

o

u

 

t

o

 

a

s

s

a

s

s

i

n

a

t

e

 

a

 

Q

e

y

n

o

s

 

g

u

a

r

d

 

b

y

 

t

h

e

 

n

a

m

e

 

o

f

 

N

a

s

h

.

 

H

e

 

h

a

s

 

b

e

e

n

 

a

 

t

h

o

r

n

 

i

n

 

o

u

r

 

s

i

d

e

 

f

o

r

 

s

o

m

e

 

t

i

m

e

.

 

B

r

i

n

g

 

m

e

 

h

i

s

 

h

e

a

d

 

a

n

d

 

I

 

s

h

a

l

l

 

d

e

f

i

l

e

 

o

n

e

 

o

f

 

t

h

e

s

e

 

b

e

a

r

s

 

f

o

r

 

y

o

u

.




e

l

s

e

i

f

(

t

e

l

l

p

a

u

s

e

 

=

=

 

5

)

 

t

h

e

n




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

1

8

3

0

,

1

3

1

6

,

-

1

2

,

2

2

0

,

t

r

u

e

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

S

e

c

r

e

t

s

*




a

l

r

e

a

d

y

_

t

e

l

l

 

=

 

0

;




t

e

l

l

p

a

u

s

e

 

=

 

0

;






















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

8

2

7

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

8

2

7

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

H

e

a

d

 

o

f

 

G

u

a

r

d

 

N

a

s

h

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

F

a

r

k

u

s

 

G

r

i

m

e

 

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

'

v

e

 

d

o

n

e

 

w

e

l

l

,

 

I

 

s

e

e

 

w

e

 

a

r

e

 

o

f

 

a

 

l

i

k

e

 

m

i

n

d

.

 

I

'

l

l

 

l

u

r

e

 

t

h

e

 

b

e

a

r

 

o

u

t

s

i

d

e

 

s

o

 

y

o

u

 

c

a

n

 

d

o

 

y

o

u

r

 

w

o

r

k

.




e

q

.

s

t

a

r

t

(

4

1

)

;







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

 

3

)

 

t

h

e

n




>

*

F

a

r

k

u

s

 

G

r

i

m

e

 

h

o

l

d

s

 

a

 

b

i

t

 

o

f

 

f

o

o

d

 

o

u

t

 

t

o

 

t

h

e

 

b

e

a

r

 

c

u

b

,

 

'

W

a

n

t

 

i

t

?

'

*




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

a

 

d

o

c

i

l

e

 

b

e

a

r

]

(

/

n

p

c

/

1

8

1

1

0

2

)




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

F

a

r

k

u

s

 

G

r

i

m

e

 

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

 

t

h

e

n

 

l

i

t

t

l

e

 

b

e

a

r




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

 

5

)

 

t

h

e

n




>

*

F

a

r

k

u

s

 

G

r

i

m

e

 

g

i

v

e

s

 

t

h

e

 

b

e

a

r

 

t

h

e

 

t

a

i

n

t

e

d

 

f

o

o

d

.

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

 

6

)

 

t

h

e

n




>

*

*

F

a

r

k

u

s

 

G

r

i

m

e

 

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

 

d

i

s

e

a

s

e

d

 

w

i

t

h

i

n

 

t

h

i

s

 

f

o

o

d

 

a

c

t

s

 

v

e

r

y

 

q

u

i

c

k

l

y

.

 

 

T

h

e

 

b

e

a

r

 

s

h

o

u

l

d

 

b

e

 

m

a

d

d

e

n

e

d

 

b

y

 

t

h

e

 

i

l

l

n

e

s

s

 

s

h

o

r

t

l

y

 

a

n

d

 

h

i

s

 

l

i

v

e

r

 

s

u

i

t

a

b

l

e

 

f

o

r

 

h

a

r

v

e

s

t

.




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

a

 

d

o

c

i

l

e

 

b

e

a

r

]

(

/

n

p

c

/

1

8

1

1

0

2

)





