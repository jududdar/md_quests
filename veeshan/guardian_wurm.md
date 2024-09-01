# guardian wurm

[guardian wurm](/npc/108506) is a level 60 Wurm Warrior that spawns in [Veeshan's Peak](/zone/108).

Their primary faction is [Minions of Scale](/faction/455).f

u

n

c

t

i

o

n

 

e

v

e

n

t

_

d

e

a

t

h

_

c

o

m

p

l

e

t

e

(

e

v

e

n

t

)







i

f

 

(

 

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

)

 

<

 

0

.

1

0

 

)

 

t

h

e

n







f

u

n

c

t

i

o

n

 

g

e

t

R

a

n

d

o

m

W

u

r

m

(

)




l

o

c

a

l

 

r

a

n

d

o

m

W

u

r

m

 

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

)

;







i

f

 

(

 

r

a

n

d

o

m

W

u

r

m

 

>

 

5

 

)

 

t

h

e

n




r

a

n

d

o

m

W

u

r

m

 

=

 

1

0

8

5

0

6

;







e

l

s

e

i

f

 

(

 

r

a

n

d

o

m

W

u

r

m

 

=

=

 

1

 

)

 

t

h

e

n




r

a

n

d

o

m

W

u

r

m

 

=

 

1

0

8

5

2

0

;







e

l

s

e

i

f

 

(

 

r

a

n

d

o

m

W

u

r

m

 

=

=

 

2

 

)

 

t

h

e

n




r

a

n

d

o

m

W

u

r

m

 

=

 

1

0

8

5

2

1

;







e

l

s

e

i

f

 

(

 

r

a

n

d

o

m

W

u

r

m

 

=

=

 

3

 

)

 

t

h

e

n




r

a

n

d

o

m

W

u

r

m

 

=

 

1

0

8

5

2

2

;







e

l

s

e

i

f

 

(

 

r

a

n

d

o

m

W

u

r

m

 

=

=

 

4

 

)

 

t

h

e

n




r

a

n

d

o

m

W

u

r

m

 

=

 

1

0

8

5

2

3

;







e

l

s

e

i

f

 

(

 

r

a

n

d

o

m

W

u

r

m

 

=

=

 

5

 

)

 

t

h

e

n




r

a

n

d

o

m

W

u

r

m

 

=

 

1

0

8

5

2

4

;










r

e

t

u

r

n

 

r

a

n

d

o

m

W

u

r

m

;










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

g

e

t

R

a

n

d

o

m

W

u

r

m

(

)

,

 

0

,

 

0

,

 

e

v

e

n

t

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

v

e

n

t

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

v

e

n

t

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

 

e

v

e

n

t

.

s

e

l

f

:

G

e

t

H

e

a

d

i

n

g

(

)

)

;







i

f

 

(

 

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

)

 

<

 

0

.

5

 

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

g

e

t

R

a

n

d

o

m

W

u

r

m

(

)

,

 

0

,

 

0

,

 

e

v

e

n

t

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

v

e

n

t

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

v

e

n

t

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

 

e

v

e

n

t

.

s

e

l

f

:

G

e

t

H

e

a

d

i

n

g

(

)

)

;








