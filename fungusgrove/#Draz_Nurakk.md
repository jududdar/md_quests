# Draz Nurakk

[Draz Nurakk](/npc/157009) is a level 55 Iksar Beastlord that spawns in [The Fungus Grove](/zone/157).

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

 

3

6

0

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

e

p

o

p

*




*

*

D

e

s

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

D

r

a

z

 

N

u

r

a

k

k

s

 

W

a

r

d

e

r

]

(

/

n

p

c

/

1

5

7

0

6

9

)




*

*

D

r

a

z

 

N

u

r

a

k

k

 

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

 

D

r

a

z

 

N

u

r

a

k

k

 

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

5

7

0

6

9

)

:

A

d

d

T

o

H

a

t

e

L

i

s

t

(

e

.

o

t

h

e

r

,

1

)

;




i

f

(

n

o

t

 

e

q

.

i

s

_

p

a

u

s

e

d

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

)

 

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

D

r

a

z

 

N

u

r

a

k

k

s

 

W

a

r

d

e

r

]

(

/

n

p

c

/

1

5

7

0

6

9

)


