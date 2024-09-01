# Lord Kreizenn

[Lord Kreizenn](/npc/124074) is a level 66 Dragon Monk that spawns in [Temple of Veeshan](/zone/124).

Their primary faction is [Guardians of Veeshan](/faction/467).











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

a

 

g

u

a

r

d

i

a

n

 

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

1

2

4

1

5

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

 

5

0

9

,

 

*

*

x

:

*

*

 

-

8

1

0

)










f

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

(

e

)







l

o

c

a

l

 

n

p

c

_

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

:

G

e

t

N

P

C

L

i

s

t

(

)

;







i

f

 

(

 

n

p

c

_

l

i

s

t

 

)

 

t

h

e

n




f

o

r

 

n

p

c

 

i

n

 

n

p

c

_

l

i

s

t

.

e

n

t

r

i

e

s

 

d

o




i

f

 

(

 

n

p

c

:

G

e

t

N

P

C

T

y

p

e

I

D

(

)

 

=

=

 

1

2

4

1

5

7

 

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

X

(

)

 

=

=

 

-

8

1

0

 

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

Y

(

)

 

=

=

 

5

0

9

 

)

 

t

h

e

n




n

p

c

:

D

e

p

o

p

(

)

;




b

r

e

a

k

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

 

 

L

o

r

d

 

K

r

e

i

z

e

n

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

h

e

l

p

*

 

f

o

r

 

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




H

e

l

p

M

e

(

e

)

;




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

h

e

l

p

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

h

e

l

p

"

)

 

t

h

e

n




H

e

l

p

M

e

(

e

)

;













f

u

n

c

t

i

o

n

 

H

e

l

p

M

e

(

e

)




l

o

c

a

l

 

a

a

r

y

o

n

a

r

 

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

2

4

0

1

0

)

;







i

f

 

(

a

a

r

y

o

n

a

r

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




a

a

r

y

o

n

a

r

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

:

M

o

v

e

T

o

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

,

 

f

a

l

s

e

)

;





