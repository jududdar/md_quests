# a greedy beggar

[a greedy beggar](/npc/68006) is a level 1 Halfling Rogue that spawns in [Butcherblock Mountains](/zone/68).

Their primary faction is [Guardians of the Vale](/faction/263).l

o

c

a

l

 

f

o

l

l

o

w

t

a

r

g

e

t

;




l

o

c

a

l

 

s

k

i

p

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




f

o

l

l

o

w

t

a

r

g

e

t

 

=

 

n

i

l

;




s

k

i

p

 

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

a

 

g

r

e

e

d

y

 

b

e

g

g

a

r

 

s

a

y

s

:

*

*

 

H

e

l

l

o

 

t

h

e

r

e

 

S

o

a

n

d

s

o

.

 

I

 

d

o

n

'

t

 

s

u

p

p

o

s

e

 

y

o

u

 

c

a

n

 

s

p

a

r

e

 

s

o

m

e

 

c

o

i

n

s

?

 

I

'

m

 

j

u

s

t

 

a

 

p

o

o

r

 

h

a

l

f

l

i

n

g

 

t

h

a

t

 

i

s

 

f

a

r

 

a

w

a

y

 

f

r

o

m

 

h

o

m

e

.

 

I

 

c

a

n

'

t

 

a

f

f

o

r

d

 

a

n

y

t

h

i

n

g

 

t

o

 

e

a

t

 

o

r

 

d

r

i

n

k

.

 

A

n

y

t

h

i

n

g

 

y

o

u

 

c

a

n

 

o

f

f

e

r

 

m

e

 

w

i

l

l

 

b

e

 

o

f

 

h

e

l

p

.




i

f

(

f

o

l

l

o

w

t

a

r

g

e

t

 

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




f

o

l

l

o

w

t

a

r

g

e

t

 

=

 

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

I

D

(

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

A

p

p

e

a

r

a

n

c

e

(

0

)

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

f

o

l

l

o

w

*

 

f

o

r

 

3

 

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

f

o

l

l

o

w

"

 

a

n

d

 

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

C

l

i

e

n

t

B

y

I

D

(

f

o

l

l

o

w

t

a

r

g

e

t

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

 

s

k

i

p

 

=

=

 

0

)

 

t

h

e

n




e

q

.

f

o

l

l

o

w

(

f

o

l

l

o

w

t

a

r

g

e

t

)

;

 




e

l

s

e




i

f

(

s

k

i

p

 

=

=

 

0

)

 

t

h

e

n




s

k

i

p

 

=

 

1

;




e

q

.

s

t

o

p

_

f

o

l

l

o

w

(

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

A

p

p

e

a

r

a

n

c

e

(

3

)

;

 




e

l

s

e

i

f

(

s

k

i

p

 

=

=

 

1

)

 

t

h

e

n




s

k

i

p

 

=

 

0

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

f

o

l

l

o

w

*




f

o

l

l

o

w

t

a

r

g

e

t

 

=

 

n

i

l

;




e

.

s

e

l

f

:

M

o

v

e

T

o

(

2

4

0

7

,

1

4

8

2

,

0

,

1

6

8

,

t

r

u

e

)

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

f

o

l

l

o

w

t

a

r

g

e

t

 

=

=

 

n

i

l

 

o

r

 

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

I

D

(

)

 

=

=

 

f

o

l

l

o

w

t

a

r

g

e

t

)

 

t

h

e

n




>

*

*

a

 

g

r

e

e

d

y

 

b

e

g

g

a

r

 

s

a

y

s

:

*

*

 

O

h

 

t

h

a

n

k

 

y

o

u

.

 

Y

o

u

 

a

r

e

 

t

o

o

 

k

i

n

d

 

t

o

 

t

h

i

s

 

p

o

o

r

 

h

a

l

f

l

i

n

g

.

 

D

o

 

y

o

u

 

h

a

v

e

 

a

n

y

t

h

i

n

g

 

e

l

s

e

 

t

o

 

g

i

v

e

 

m

e

?




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

A

p

p

e

a

r

a

n

c

e

(

0

)

;

 




f

o

l

l

o

w

t

a

r

g

e

t

 

=

 

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

I

D

(

)

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

f

o

l

l

o

w

*

 

f

o

r

 

3

 

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








