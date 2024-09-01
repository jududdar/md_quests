# Legionnaire Claudius

[Legionnaire Claudius](/npc/160136) is a level 1 Human Warrior that spawns in [Katta Castellum](/zone/160).





#

#

 

D

i

a

l

o

g




l

o

c

a

l

 

v

a

h

n

 

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

3

7

)

;




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

a

i

t

o

r

 

t

o

 

t

h

e

 

V

a

l

i

d

u

s

 

C

u

s

t

o

d

u

s

`







i

f

(

v

a

h

n

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

\

#

V

a

h

n

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

4

0

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

 

,

 

*

*

x

:

*

*

 

)




*

*

D

e

s

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

V

a

h

n

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

3

7

)




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

\

#

\

#

L

e

g

i

o

n

n

a

i

r

e

 

C

l

a

u

d

i

u

s

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

4

1

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

 

,

 

*

*

x

:

*

*

 

)




*

*

L

e

g

i

o

n

n

a

i

r

e

 

C

l

a

u

d

i

u

s

 

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




l

o

c

a

l

 

v

a

h

n

 

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

3

7

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

 

3

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

V

a

h

n

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

3

7

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

 

6

7

,

 

*

*

x

:

*

*

 

-

1

1

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

5

)

 

t

h

e

n




i

f

(

v

a

h

n

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




v

a

h

n

:

E

m

o

t

e

(

"

s

p

e

a

k

s

 

w

i

t

h

 

L

e

g

i

o

n

n

a

i

r

e

 

C

l

a

u

d

i

u

s

 

i

n

 

h

u

s

h

e

d

 

t

o

n

e

s

.

 

T

h

e

i

r

 

w

h

i

s

p

e

r

s

 

c

a

n

n

o

t

 

b

e

 

h

e

a

r

d

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

 

c

e

r

t

a

i

n

l

y

 

s

o

m

e

t

h

i

n

g

 

s

u

s

p

i

c

i

o

u

s

 

i

n

 

t

h

e

i

r

 

d

e

m

e

a

n

o

r

.

"

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

6

)

 

t

h

e

n




i

f

(

v

a

h

n

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




v

a

h

n

:

E

m

o

t

e

(

"

p

a

s

s

e

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

 

t

o

 

C

l

a

u

d

i

u

s

 

a

n

d

 

g

e

t

s

 

a

 

r

o

l

l

e

d

 

u

p

 

p

a

r

c

h

m

e

n

t

 

i

n

 

r

e

t

u

r

n

.

 

T

h

e

i

r

 

b

u

s

i

n

e

s

s

 

a

p

p

e

a

r

s

 

t

o

 

b

e

 

c

o

m

p

l

e

t

e

d

 

a

n

d

 

b

o

t

h

 

p

a

r

t

i

e

s

 

p

r

e

p

a

r

e

 

t

o

 

g

o

 

a

b

o

u

t

 

t

h

e

i

r

 

b

u

s

i

n

e

s

s

.

"

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

7

)

 

t

h

e

n




i

f

(

v

a

h

n

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




v

a

h

n

:

E

m

o

t

e

(

"

g

l

a

n

c

e

s

 

i

n

 

e

i

t

h

e

r

 

d

i

r

e

c

t

i

o

n

 

a

n

d

 

n

o

d

s

 

a

t

 

C

l

a

u

d

i

u

s

 

b

e

f

o

r

e

 

d

i

s

a

p

p

e

a

r

i

n

g

 

b

a

c

k

 

i

n

t

o

 

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

.

"

)

;




>

*

L

e

g

i

o

n

n

a

i

r

e

 

C

l

a

u

d

i

u

s

 

l

o

o

k

s

 

t

o

 

V

a

h

n

 

t

e

n

t

a

t

i

v

e

l

y

,

 

'

W

e

 

s

h

a

l

l

 

m

e

e

t

 

a

g

a

i

n

 

s

o

o

n

.

'

*




v

a

h

n

:

S

a

y

(

"

P

e

r

h

a

p

s

"

)

;




v

a

h

n

:

E

m

o

t

e

(

"

s

t

e

p

s

 

o

u

t

 

o

f

 

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

 

a

s

 

t

h

o

u

g

h

 

a

p

p

e

a

r

i

n

g

 

o

u

t

 

o

f

 

t

h

i

n

 

a

i

r

.

"

)

;







*

*

D

e

s

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

V

a

h

n

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

3

7

)




*

*

L

e

g

i

o

n

n

a

i

r

e

 

C

l

a

u

d

i

u

s

 

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





