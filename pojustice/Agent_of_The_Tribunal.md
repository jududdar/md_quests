# Agent of The Tribunal

[Agent of The Tribunal](/npc/201075) is a level 60 Guard of Justice Warrior that spawns in [Plane of Justice](/zone/201).l

o

c

a

l

 

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

_

I

D

S

 

=

 

{

 

[

3

4

5

3

1

4

]

 

=

 

1

,

 

[

3

4

5

3

1

8

]

 

=

 

2

,

 

[

3

4

5

3

1

3

]

 

=

 

3

,

 

[

3

4

5

3

1

5

]

 

=

 

4

,

 

[

3

4

5

3

1

6

]

 

=

 

5

,

 

[

3

4

5

3

1

7

]

 

=

 

6

 

}

;




l

o

c

a

l

 

C

O

N

T

R

O

L

L

E

R

_

I

D

S

 

=

 

{

 

2

0

1

5

1

2

,

 

2

0

1

5

1

1

,

 

2

0

1

5

1

3

,

 

2

0

1

5

1

4

,

 

2

0

1

5

1

5

,

 

2

0

1

5

1

0

 

}

;













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

 

t

r

i

a

l

N

u

m

 

=

 

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

_

I

D

S

[

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

S

p

a

w

n

P

o

i

n

t

I

D

(

)

]

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

h

a

i

l

`







>

*

*

A

g

e

n

t

 

o

f

 

T

h

e

 

T

r

i

b

u

n

a

l

 

s

a

y

s

:

*

*

 

A

r

e

 

y

o

u

 

r

e

a

d

y

 

t

o

 

[

r

e

t

u

r

n

]

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

r

e

t

u

r

n

`







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

C

O

N

T

R

O

L

L

E

R

_

I

D

S

[

t

r

i

a

l

N

u

m

]

)

 

)

 

t

h

e

n




>

*

*

A

g

e

n

t

 

o

f

 

T

h

e

 

T

r

i

b

u

n

a

l

 

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

 

t

r

i

a

l

 

i

s

 

y

e

t

 

u

n

d

e

r

w

a

y

.

 

 

Y

o

u

 

m

u

s

t

 

w

a

i

t

.




e

l

s

e




e

.

o

t

h

e

r

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

1

,

 

4

7

3

,

 

6

8

5

,

 

1

0

,

 

0

)

;




i

f

 

(

 

e

.

o

t

h

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

 

e

.

o

t

h

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




e

.

o

t

h

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

4

7

3

,

 

6

8

5

,

 

1

0

,

 

0

)

;











