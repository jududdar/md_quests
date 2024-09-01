# A Castellan of Air

[A Castellan of Air](/npc/215000) is a level 63 Animated Armor Paladin that spawns in [Plane of Air](/zone/215).

Their primary faction is [KOS](/faction/5017).l

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

T

Y

P

E

 

=

 

2

1

5

4

1

9

;

 




l

o

c

a

l

 

I

N

L

O

K

H

E

R

_

T

Y

P

E

 

=

 

2

1

5

4

0

9

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







e

q

.

s

i

g

n

a

l

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

T

Y

P

E

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

\

#

C

o

n

s

t

a

b

l

e

 

A

l

r

a

n

d

e

r

i

s

a

n

]

(

/

n

p

c

/

2

1

5

3

8

3

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

\

#

C

o

n

s

t

a

b

l

e

 

B

e

l

e

c

o

h

e

n

]

(

/

n

p

c

/

2

1

5

3

8

4

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

\

#

C

o

n

s

t

a

b

l

e

 

F

e

r

a

b

a

l

e

n

]

(

/

n

p

c

/

2

1

5

3

8

5

)







l

o

c

a

l

 

r

o

l

l

 

=

 

m

a

t

h

.

r

a

n

d

o

m

(

1

,

1

0

0

)

;







i

f

 

(

 

r

o

l

l

 

<

 

6

 

a

n

d

 

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

I

N

L

O

K

H

E

R

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

I

N

L

O

K

H

E

R

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

,

 

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

,

 

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

Z

(

)

,

 

0

)

;










r

o

l

l

 

=

 

m

a

t

h

.

r

a

n

d

o

m

(

1

,

 

4

)

;







f

o

r

 

i

 

=

 

1

,

 

r

o

l

l

 

d

o




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

A

 

V

e

n

g

e

f

u

l

 

A

i

r

s

p

i

r

i

t

]

(

/

n

p

c

/

2

1

5

4

1

3

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





