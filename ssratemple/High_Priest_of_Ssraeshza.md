# High Priest of Ssraeshza

[High Priest of Ssraeshza](/npc/162076) is a level 66 Shissar Cleric that spawns in [Ssraeshza Temple](/zone/162).

Their primary faction is [Brood of Ssraeshza](/faction/1535).





l

o

c

a

l

 

A

D

D

_

T

Y

P

E

S

 

=

 

{

 

1

6

2

1

1

5

,

 

1

6

2

1

1

2

,

 

1

6

2

1

1

4

,

 

1

6

2

1

1

3

,

 

1

6

2

1

2

1

,

 

1

6

2

1

1

9

,

 

1

6

2

1

2

2

,

 

1

6

2

1

2

0

,

 

1

6

2

1

1

8

,

 

1

6

2

1

1

6

,

 

1

6

2

1

1

7

,

 

1

6

2

1

1

1

 

}

;













#

#

 

C

o

m

b

a

t




i

f

 

 

H

i

g

h

 

P

r

i

e

s

t

 

o

f

 

S

s

r

a

e

s

h

z

a

 

e

n

t

e

r

s

 

c

o

m

b

a

t

 

 

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

c

h

e

c

k

*

 

f

o

r

 

1

0

 

s

e

c

o

n

d

s




e

l

s

e




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

*



















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

"

 

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

 

e

l

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

;




l

o

c

a

l

 

n

p

c

;







f

o

r

 

_

,

 

t

y

p

 

i

n

 

i

p

a

i

r

s

(

A

D

D

_

T

Y

P

E

S

)

 

d

o




n

p

c

 

=

 

e

l

i

s

t

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

t

y

p

)

:

C

a

s

t

T

o

N

P

C

(

)

;




i

f

 

(

 

n

p

c

 

a

n

d

 

n

p

c

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

p

c

:

G

e

t

Z

(

)

 

<

 

2

4

0

 

)

 

t

h

e

n




n

p

c

:

G

M

M

o

v

e

(

n

p

c

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

X

(

)

,

 

n

p

c

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

Y

(

)

,

 

n

p

c

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

Z

(

)

,

 

n

p

c

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

H

(

)

)

;




n

p

c

:

C

a

s

t

S

p

e

l

l

(

3

2

3

0

,

 

n

p

c

:

G

e

t

I

D

(

)

)

;

 




n

p

c

:

W

i

p

e

H

a

t

e

L

i

s

t

(

)

;




r

e

t

u

r

n

;

 











