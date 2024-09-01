# Maidens Voyage

[Maidens Voyage](/npc/838) is a level 50 Ship Warrior that spawns in [Timorous Deep](/zone/96).





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




i

f

 

(

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

g

u

i

l

d

_

i

d

(

)

 

~

=

 

-

1

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

W

e

 

a

r

e

 

i

n

 

a

n

 

i

n

s

t

a

n

c

e

 

(

"

 

.

.

 

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

g

u

i

l

d

_

i

d

(

)

 

.

.

 

"

)

,

 

i

g

n

o

r

i

n

g

 

e

v

e

n

t

_

s

p

a

w

n

 

f

o

r

 

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

N

a

m

e

(

)

)

;




*

*

M

a

i

d

e

n

s

 

V

o

y

a

g

e

 

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

B

o

a

t

 

s

p

a

w

n

e

d

!

 

N

a

m

e

 

i

s

:

 

M

a

i

d

e

n

s

 

V

o

y

a

g

e

 

T

i

m

e

 

i

s

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

"

,

 

1

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

I

s

l

a

n

d

 

S

h

u

t

t

l

e

]

(

/

n

p

c

/

9

6

0

7

5

)




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

B

o

a

t

 

t

o

 

f

i

r

i

o

n

a

 

(

2

)

 

h

a

s

 

r

e

a

c

h

e

d

 

t

h

e

 

E

l

f

 

d

o

c

k

s

.

 

N

a

m

e

 

i

s

:

 

M

a

i

d

e

n

s

 

V

o

y

a

g

e

 

T

i

m

e

 

i

s

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

I

s

l

a

n

d

 

S

h

u

t

t

l

e

]

(

/

n

p

c

/

9

6

0

7

5

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

 

1

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

B

o

a

t

 

t

o

 

f

i

r

i

o

n

a

 

(

2

)

 

h

a

s

 

r

e

a

c

h

e

d

 

t

h

e

 

s

h

u

t

t

l

e

.

 

N

a

m

e

 

i

s

:

 

M

a

i

d

e

n

s

 

V

o

y

a

g

e

 

T

i

m

e

 

i

s

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

"

,

 

1

)

;




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

h

u

t

t

l

e

 

I

]

(

/

n

p

c

/

8

4

6

)




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

h

u

t

t

l

e

 

I

I

]

(

/

n

p

c

/

8

4

7

)




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

h

u

t

t

l

e

 

I

I

I

]

(

/

n

p

c

/

8

4

8

)




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

h

u

t

t

l

e

 

I

V

]

(

/

n

p

c

/

8

4

9

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

 

3

0

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

B

o

a

t

 

t

o

 

f

i

r

i

o

n

a

 

(

2

)

 

h

a

s

 

r

e

a

c

h

e

d

 

i

t

s

 

d

e

s

t

i

n

a

t

i

o

n

!

 

N

a

m

e

 

i

s

:

 

M

a

i

d

e

n

s

 

V

o

y

a

g

e

 

T

i

m

e

 

i

s

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

"

,

 

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

F

o

r

e

a

c

h

C

l

i

e

n

t

(




f

u

n

c

t

i

o

n

(

e

n

t

)




e

n

t

:

S

i

g

n

a

l

(

1

)

;




e

n

d

,




f

u

n

c

t

i

o

n

(

e

n

t

)




l

o

c

a

l

 

p

x

 

=

 

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

;




l

o

c

a

l

 

p

y

 

=

 

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

;




l

o

c

a

l

 

b

o

a

t

_

i

d

 

=

 

e

n

t

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

;




l

o

c

a

l

 

d

i

f

f

_

b

o

a

t

_

c

h

e

c

k

 

=

 

b

o

a

t

_

i

d

 

=

=

 

9

6

0

7

5

 

o

r

 

b

o

a

t

_

i

d

 

=

=

 

8

4

6

 

o

r

 

b

o

a

t

_

i

d

 

=

=

 

8

4

7

 

o

r

 

b

o

a

t

_

i

d

 

=

=

 

8

4

8

 

o

r

 

b

o

a

t

_

i

d

 

=

=

 

8

4

9

;







l

o

c

a

l

 

v

a

l

i

d

_

p

o

s

_

c

h

e

c

k

 

=

 

p

x

 

>

=

 

-

3

0

0

0

 

a

n

d

 

p

x

 

<

=

 

-

1

7

0

0

 

a

n

d

 

p

y

 

>

=

 

0

 

a

n

d

 

p

y

 

<

=

 

1

8

0

0

;







i

f

(

d

i

f

f

_

b

o

a

t

_

c

h

e

c

k

 

a

n

d

 

v

a

l

i

d

_

p

o

s

_

c

h

e

c

k

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

F

o

r

e

a

c

h

C

l

i

e

n

t

(




f

u

n

c

t

i

o

n

(

e

n

t

)




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

8

4

,

4

4

2

1

,

-

5

6

8

5

,

-

6

7

,

 

0

)

;




e

n

d

,




f

u

n

c

t

i

o

n

(

e

n

t

)




i

f

(

e

n

t

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

 

8

3

8

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







)

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

 

5

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

G

l

i

s

s

e

 

B

l

u

e

s

e

a

]

(

/

n

p

c

/

6

8

2

3

6

)





