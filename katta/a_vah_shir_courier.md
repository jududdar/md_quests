# a vah shir courier

[a vah shir courier](/npc/160171) is a level 38 Vah Shir Warrior that spawns in [Katta Castellum](/zone/160).





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

r

u

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

r

u

n

"

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




r

o

s

h

 

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

1

6

0

1

2

6

)

;




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




i

f

(

r

o

s

h

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




>

*

*

a

 

v

a

h

 

s

h

i

r

 

c

o

u

r

i

e

r

 

s

a

y

s

:

*

*

 

S

o

r

r

y

 

f

o

r

 

t

h

e

 

d

e

l

a

y

 

m

i

s

t

r

e

s

s

,

 

I

 

r

a

n

 

i

n

t

o

 

a

 

s

p

o

t

 

o

f

 

t

r

o

u

b

l

e

 

o

n

 

t

h

e

 

w

a

y

 

h

e

r

e

.

 

I

 

a

m

 

p

r

e

p

a

r

e

d

 

t

o

 

d

e

l

i

v

e

r

 

y

o

u

r

 

c

r

a

t

e

 

t

o

 

t

h

e

 

s

p

i

r

i

t

i

s

t

s

 

b

a

c

k

 

h

o

m

e

.




r

o

s

h

:

S

a

y

(

"

I

 

h

o

p

e

 

y

o

u

r

 

j

o

u

r

n

e

y

 

b

a

c

k

 

t

o

 

S

h

a

r

 

V

a

h

l

 

i

s

 

l

e

s

s

 

e

v

e

n

t

f

u

l

.

 

P

l

e

a

s

e

 

m

a

k

e

 

h

a

s

t

e

,

 

t

h

e

 

s

p

i

r

i

t

i

s

t

s

 

m

u

s

t

 

r

e

c

e

i

v

e

 

t

h

i

s

 

c

r

a

t

e

 

a

s

 

s

o

o

n

 

a

s

 

p

o

s

s

i

b

l

e

.

"

)

;




>

*

a

 

v

a

h

 

s

h

i

r

 

c

o

u

r

i

e

r

 

t

u

c

k

s

 

t

h

e

 

c

r

a

t

e

 

o

f

 

s

k

u

l

l

s

 

u

n

d

e

r

 

h

i

s

 

a

r

m

 

a

n

d

 

n

o

d

s

 

t

o

 

R

o

s

h

a

w

n

a

.

 

S

u

d

d

e

n

l

y

 

t

h

e

 

c

o

u

r

i

e

r

 

b

e

g

i

n

s

 

t

o

 

s

h

a

k

e

,

 

h

i

s

 

f

u

r

 

s

t

a

n

d

s

 

o

n

 

e

n

d

,

 

a

n

d

 

h

i

s

 

e

y

e

s

 

g

l

a

z

e

 

o

v

e

r

 

e

x

p

r

e

s

s

i

o

n

l

e

s

s

l

y

.

 

T

h

e

 

c

o

u

r

i

e

r

 

r

u

n

s

 

f

o

r

 

t

h

e

 

g

a

t

e

s

 

o

f

 

K

a

t

t

a

 

C

a

s

t

e

l

l

u

m

 

w

i

t

h

 

a

n

 

o

t

h

e

r

w

o

r

l

d

l

y

 

h

o

w

l

 

e

c

h

o

i

n

g

 

i

n

 

h

i

s

 

w

a

k

e

.

*




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

I

t

e

m

(

1

7

0

7

9

,

1

)

;




r

o

s

h

:

S

a

y

(

"

S

t

o

p

 

h

i

m

!

 

S

t

o

p

 

t

h

e

 

c

o

u

r

i

e

r

!

 

A

n

 

e

v

i

l

 

s

p

i

r

i

t

 

h

a

s

 

p

o

s

s

e

s

s

e

d

 

h

i

m

!

 

H

e

 

m

u

s

t

 

n

o

t

 

e

s

c

a

p

e

 

w

i

t

h

 

t

h

o

s

e

 

s

k

u

l

l

s

!

 

C

a

t

c

h

 

h

i

m

 

a

n

d

 

b

r

i

n

g

 

b

a

c

k

 

t

h

a

t

 

c

r

a

t

e

 

o

f

 

s

k

u

l

l

s

!

"

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






















#

#

 

O

n

 

N

P

C

 

D

e

a

t

h




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

W

a

y

p

o

i

n

t

I

D

(

)

 

>

 

8

 

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

W

a

y

p

o

i

n

t

I

D

(

)

 

<

=

 

1

4

)

 

t

h

e

n




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

n

.




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

n

.




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

n

.




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

n

.




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

n

.




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

n

.




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

n

.




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

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

s

e

l

f

:

G

e

t

W

a

y

p

o

i

n

t

I

D

(

)

 

>

 

1

4

)

 

t

h

e

n




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

n

.




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

n

.




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

n

.




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

n

.




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

n

.




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

n

.




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

a

 

r

e

a

n

i

m

a

t

e

d

 

V

a

h

 

S

h

i

r

]

(

/

n

p

c

/

1

6

0

1

7

2

)

 

a

t

 

t

h

i

s

 

l

o

c

a

t

i

o

n

.





