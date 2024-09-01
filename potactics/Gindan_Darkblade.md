# Gindan Darkblade

[Gindan Darkblade](/npc/214032) is a level 65 Rallos Zek Minion Warrior that spawns in [Drunder, the Fortress of Zek](/zone/214).

Their primary faction is [The Gindan](/faction/1644).





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

 

=

=

 

0

 

)

 

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

d

e

p

o

p

*

 

f

o

r

 

3

6

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

S

p

e

c

i

a

l

A

b

i

l

i

t

y

(

4

9

,

 

1

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

h

p

"

 

)

 

t

h

e

n







i

f

 

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

H

P

R

a

t

i

o

(

)

 

<

 

5

0

 

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

1

,

1

0

0

)

 

<

 

2

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

t

o

p

_

t

i

m

e

r

(

e

.

t

i

m

e

r

)

;




e

l

s

e




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

G

i

n

d

a

n

 

D

a

r

k

b

l

a

d

e

]

(

/

n

p

c

/

2

1

4

0

3

2

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

G

i

n

d

a

n

 

D

a

r

k

b

l

a

d

e

]

(

/

n

p

c

/

2

1

4

0

3

2

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




*

*

G

i

n

d

a

n

 

D

a

r

k

b

l

a

d

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

G

i

n

d

a

n

 

D

a

r

k

b

l

a

d

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

 

 

G

i

n

d

a

n

 

D

a

r

k

b

l

a

d

e

 

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




i

f

 

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

 

>

 

0

 

)

 

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

h

p

*

 

f

o

r

 

5

 

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

c

h

e

c

k

h

p

*





