# Bilf

[Bilf](/npc/110056) is a level 26 Gnome Rogue that spawns in [Iceclad Ocean](/zone/110).

Their primary faction is [Pirates of Iceclad](/faction/447).l

o

c

a

l

 

c

o

u

n

t

 

=

 

0

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

o

l

l

*

 

f

o

r

 

7

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

B

i

l

f

 

s

a

y

s

:

*

*

 

S

h

o

v

e

 

o

f

f

,

 

m

a

t

e

.

 

 

W

e

'

r

e

 

b

u

s

y

 

'

s

c

o

u

t

i

n

'

.

 

 

C

a

n

'

t

 

y

a

 

s

e

e

?

 

 

H

e

h

e

h

e

!




i

f

(

*

*

s

p

a

w

n

e

d

 

N

P

C

:

*

*

 

 

[

B

l

i

k

]

(

/

n

p

c

/

1

1

0

0

5

4

)

)

 

t

h

e

n




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

1

0

0

5

4

)

:

S

a

y

(

"

H

a

r

 

h

a

r

!

 

 

S

c

o

u

t

i

n

'

.

 

 

Y

a

h

,

 

t

h

a

t

s

 

w

h

a

t

 

w

e

 

b

e

 

d

o

i

n

'

!

"

)

;







i

f

(

*

*

s

p

a

w

n

e

d

 

N

P

C

:

*

*

 

 

[

F

e

l

d

]

(

/

n

p

c

/

1

1

0

0

5

5

)

)

 

t

h

e

n




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

1

0

0

5

5

)

:

S

a

y

(

"

H

a

r

 

h

a

r

!

 

 

S

c

o

u

t

i

n

'

.

 

 

Y

a

h

,

 

t

h

a

t

s

 

w

h

a

t

 

w

e

 

b

e

 

d

o

i

n

'

!

"

)

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




c

o

u

n

t

 

=

 

c

o

u

n

t

 

+

 

1

;




i

f

(

c

o

u

n

t

 

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

B

i

l

f

 

r

o

l

l

s

 

a

 

p

a

i

r

 

o

f

 

h

a

n

d

c

a

r

v

e

d

 

d

i

c

e

.

 

 

'

H

a

r

 

h

a

r

!

 

 

T

h

e

 

b

o

n

e

s

 

b

e

 

f

a

v

o

r

i

n

'

 

m

e

 

t

o

d

a

y

!

'

*




e

l

s

e

i

f

(

c

o

u

n

t

 

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

B

i

l

f

 

r

o

l

l

s

 

a

 

p

a

i

r

 

o

f

 

h

a

n

d

c

a

r

v

e

d

 

d

i

c

e

.

 

 

'

B

a

h

!

 

 

Y

o

u

 

l

o

a

d

e

d

 

t

h

e

s

e

 

d

i

c

e

!

 

 

I

 

n

e

v

e

r

 

r

o

l

l

 

t

h

i

s

 

b

a

d

!

'

*




i

f

(

*

*

s

p

a

w

n

e

d

 

N

P

C

:

*

*

 

 

[

F

e

l

d

]

(

/

n

p

c

/

1

1

0

0

5

5

)

)

 

t

h

e

n




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

1

0

0

5

5

)

:

S

a

y

(

"

I

 

a

i

n

'

t

 

l

o

a

d

e

d

 

n

o

t

h

i

n

'

.

 

 

J

u

s

t

 

r

o

l

l

 

a

n

d

 

l

o

s

e

 

y

e

r

 

c

h

i

p

s

.

 

 

H

a

r

 

h

a

r

!

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

c

o

u

n

t

 

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

B

i

l

f

 

g

e

t

s

 

a

 

s

t

r

a

n

g

e

 

s

m

i

l

e

 

a

n

d

 

t

h

r

o

w

s

 

d

o

w

n

 

a

 

c

o

u

p

l

e

 

o

f

 

c

h

i

p

s

.

 

 

'

T

i

m

e

 

t

a

 

a

n

t

e

 

u

p

.

 

 

I

'

m

 

f

e

e

l

i

n

'

 

l

u

c

k

y

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

c

o

u

n

t

 

=

=

 

4

)

 

t

h

e

n




c

o

u

n

t

 

=

 

0

;





