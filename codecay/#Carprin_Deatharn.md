# Carprin Deatharn

[Carprin Deatharn](/npc/200232) is a level 70 Knight of Pestilence Warrior that spawns in [The Crypt of Decay](/zone/200).

Their primary faction is [KOS](/faction/5017).





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

d

e

p

o

p

*

 

f

o

r

 

1

2

3

0

0

 

s

e

c

o

n

d

s




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

G

u

a

r

d

S

p

o

t

(

3

8

4

,

 

-

1

1

2

,

 

-

5

3

.

9

,

 

1

9

7

)

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

 

 

C

a

r

p

r

i

n

 

D

e

a

t

h

a

r

n

 

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




e

q

.

p

a

u

s

e

_

t

i

m

e

r

(

"

d

e

p

o

p

"

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

d

r

o

p

h

a

t

e

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




e

l

s

e




e

q

.

r

e

s

u

m

e

_

t

i

m

e

r

(

"

d

e

p

o

p

"

)

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

d

r

o

p

h

a

t

e

*



















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




*

*

Z

o

n

e

 

W

i

d

e

 

E

m

o

t

e

:

*

*

 

<

s

p

a

n

 

c

l

a

s

s

=

"

t

e

x

t

-

w

a

r

n

i

n

g

"

>

*

D

a

r

k

 

l

a

u

g

h

t

e

r

 

s

o

u

n

d

s

 

f

r

o

m

 

d

e

e

p

e

r

 

w

i

t

h

i

n

 

t

h

e

 

c

h

a

p

e

l

 

a

s

 

a

 

m

e

n

a

c

i

n

g

 

v

o

i

c

e

 

i

s

 

h

e

a

r

d

 

s

a

y

i

n

g

,

 

'

C

o

m

e

 

g

r

e

a

t

 

c

o

r

r

u

p

t

e

r

 

o

f

 

e

n

t

r

o

p

y

 

a

n

d

 

d

e

c

a

y

.

 

S

t

o

p

 

t

h

e

s

e

 

f

o

o

l

i

s

h

 

m

o

r

t

a

l

s

 

f

r

o

m

 

v

i

o

l

a

t

i

n

g

 

o

u

r

 

m

a

s

t

e

r

s

 

c

h

a

p

e

l

.

*

<

/

s

p

a

n

>




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

A

v

h

i

 

E

s

c

r

o

n

]

(

/

n

p

c

/

2

0

0

2

2

5

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

 

1

3

5

,

 

*

*

x

:

*

*

 

4

0

5

)
















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

d

r

o

p

h

a

t

e

"

)

 

t

h

e

n







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

0

1

6

6

6

 

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

 

t

a

r

g

e

t

 

=

 

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

T

a

r

g

e

t

(

)

;




i

f

 

(

 

t

a

r

g

e

t

 

a

n

d

 

t

a

r

g

e

t

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




e

.

s

e

l

f

:

R

e

m

o

v

e

F

r

o

m

H

a

t

e

L

i

s

t

(

t

a

r

g

e

t

)

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

.

.

"

 

d

r

o

p

p

e

d

 

t

a

r

g

e

t

 

f

r

o

m

 

h

a

t

e

 

l

i

s

t

 

(

"

.

.

t

a

r

g

e

t

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

.

.

"

)

"

,

 

2

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

t

i

m

e

r

 

=

=

 

"

d

e

p

o

p

"

 

)

 

t

h

e

n




*

*

C

a

r

p

r

i

n

 

D

e

a

t

h

a

r

n

 

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





