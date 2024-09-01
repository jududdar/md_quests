# Cargo Clockwork

[Cargo Clockwork](/npc/56105) is a level 30 Spider Warrior that spawns in [Steamfont Mountains](/zone/56).

Their primary faction is [Eldritch Collective](/faction/245).l

o

c

a

l

 

d

e

l

i

v

e

r

y

 

=

 

0

;













#

#

 

S

i

g

n

a

l

s




l

o

c

a

l

 

q

g

l

o

b

a

l

 

=

 

e

q

.

g

e

t

_

q

g

l

o

b

a

l

s

(

)

;







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




>

*

C

a

r

g

o

 

C

l

o

c

k

w

o

r

k

 

C

h

u

g

a

.

.

 

C

h

u

g

.

.

C

h

u

g

.

.

 

'

T

h

i

s

 

u

n

i

t

 

r

e

q

u

i

r

e

s

 

m

a

i

n

t

e

n

a

n

c

e

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

q

g

l

o

b

a

l

[

"

C

a

r

g

o

C

l

o

c

k

w

o

r

k

"

]

 

=

=

 

n

i

l

)

 

t

h

e

n




e

q

.

s

e

t

_

g

l

o

b

a

l

(

"

C

a

r

g

o

C

l

o

c

k

w

o

r

k

"

,

"

1

"

,

7

,

"

H

2

"

)

;




e

q

.

s

t

a

r

t

(

5

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

 

1

)

 

t

h

e

n




i

f

(

d

e

l

i

v

e

r

y

 

=

=

 

1

)

 

t

h

e

n




e

q

.

s

t

o

p

(

)

;




d

e

l

i

v

e

r

y

 

=

 

0

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

C

a

r

g

o

 

C

l

o

c

k

w

o

r

k

 

s

a

y

s

:

*

*

 

k

a

c

h

u

n

k

 

.

.

 

k

a

c

h

u

n

k

.

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

W

a

t

c

h

m

a

n

 

H

a

l

v

]

(

/

n

p

c

/

5

6

1

5

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

0

)

 

t

h

e

n




i

f

(

d

e

l

i

v

e

r

y

 

=

=

 

0

)

 

t

h

e

n




d

e

l

i

v

e

r

y

 

=

 

1

;




>

*

C

a

r

g

o

 

C

l

o

c

k

w

o

r

k

 

C

h

u

g

a

.

.

 

C

h

u

g

.

.

C

h

u

g

.

.

*




>

*

C

a

r

g

o

 

C

l

o

c

k

w

o

r

k

 

T

h

e

 

c

h

u

g

g

i

n

g

 

o

f

 

t

h

e

 

C

a

r

g

o

 

C

l

o

c

k

w

o

r

k

 

c

o

m

e

s

 

t

o

 

a

 

h

a

l

t

.

*




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

H

e

c

t

o

r

 

t

h

e

 

h

i

g

h

w

a

y

 

b

a

n

d

i

t

]

(

/

n

p

c

/

5

6

1

7

8

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

7

0

0

,

 

*

*

x

:

*

*

 

3

0

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

R

e

n

a

l

d

o

 

t

h

e

 

h

i

g

h

w

a

y

 

b

a

n

d

i

t

]

(

/

n

p

c

/

5

6

1

7

9

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

7

3

2

,

 

*

*

x

:

*

*

 

9

5

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

J

e

r

a

l

d

 

t

h

e

 

h

i

g

h

w

a

y

 

b

a

n

d

i

t

]

(

/

n

p

c

/

5

6

1

8

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

 

-

6

1

5

,

 

*

*

x

:

*

*

 

5

3

)




>

*

*

C

a

r

g

o

 

C

l

o

c

k

w

o

r

k

 

s

a

y

s

:

*

*

 

T

h

i

s

 

i

s

 

h

i

g

h

w

a

y

 

r

o

b

b

e

r

y

.






















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




d

e

l

i

v

e

r

y

 

=

 

0

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

H

e

c

t

o

r

 

t

h

e

 

h

i

g

h

w

a

y

 

b

a

n

d

i

t

]

(

/

n

p

c

/

5

6

1

7

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

R

e

n

a

l

d

o

 

t

h

e

 

h

i

g

h

w

a

y

 

b

a

n

d

i

t

]

(

/

n

p

c

/

5

6

1

7

9

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

J

e

r

a

l

d

 

t

h

e

 

h

i

g

h

w

a

y

 

b

a

n

d

i

t

]

(

/

n

p

c

/

5

6

1

8

0

)


