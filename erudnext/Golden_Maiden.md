# Golden Maiden

[Golden Maiden](/npc/773) is a level 50 Ship Warrior that spawns in [Erudin](/zone/24).





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




l

o

c

a

l

 

z

o

n

e

_

t

i

m

e

 

=

 

e

q

.

g

e

t

_

z

o

n

e

_

t

i

m

e

(

)

;




l

o

c

a

l

 

h

o

u

r

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

h

o

u

r

"

]

;




l

o

c

a

l

 

m

i

n

u

t

e

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

m

i

n

u

t

e

"

]

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

"

B

o

a

t

 

s

p

a

w

n

e

d

!

 

N

a

m

e

 

i

s

:

 

G

o

l

d

e

n

 

M

a

i

d

e

n

 

T

i

m

e

 

i

s

:

 

"

 

.

.

 

h

o

u

r

 

.

.

"

:

"

 

.

.

 

m

i

n

u

t

e

 

.

.

 

"

"

,

 

1

)

;



















#

#

 

A

r

r

i

v

e

 

a

t

 

W

a

y

p

o

i

n

t

 

S

c

r

i

p

t




l

o

c

a

l

 

z

o

n

e

_

t

i

m

e

 

=

 

e

q

.

g

e

t

_

z

o

n

e

_

t

i

m

e

(

)

;




l

o

c

a

l

 

h

o

u

r

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

h

o

u

r

"

]

;




l

o

c

a

l

 

m

i

n

u

t

e

 

=

 

z

o

n

e

_

t

i

m

e

[

"

z

o

n

e

_

m

i

n

u

t

e

"

]

;




i

f

(

e

.

w

p

 

=

=

 

7

)

 

t

h

e

n




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

S

a

b

r

i

n

a

]

(

/

n

p

c

/

2

4

0

5

6

)




e

l

s

e

i

f

(

e

.

w

p

 

=

=

 

8

)

 

t

h

e

n




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

S

a

b

r

i

n

a

]

(

/

n

p

c

/

2

4

0

5

6

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

R

e

k

o

 

S

a

l

t

a

m

e

r

]

(

/

n

p

c

/

2

4

0

8

5

)




e

l

s

e

i

f

(

e

.

w

p

 

=

=

 

1

0

)

 

t

h

e

n




e

q

.

d

e

b

u

g

(

"

B

o

a

t

 

t

o

 

E

r

u

d

s

x

i

n

g

 

h

a

s

 

r

e

a

c

h

e

d

 

i

t

s

 

d

e

s

t

i

n

a

t

i

o

n

!

 

N

a

m

e

 

i

s

:

 

G

o

l

d

e

n

 

M

a

i

d

e

n

 

T

i

m

e

 

i

s

:

 

"

 

.

.

 

h

o

u

r

 

.

.

"

:

"

 

.

.

 

m

i

n

u

t

e

 

.

.

 

"

"

,

 

1

)

;




e

q

.

s

p

a

w

n

_

c

o

n

d

i

t

i

o

n

(

"

e

r

u

d

n

e

x

t

"

,

1

,

0

)

;




e

q

.

s

p

a

w

n

_

c

o

n

d

i

t

i

o

n

(

"

e

r

u

d

n

e

x

t

"

,

2

,

0

)

;




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

F

o

r

e

a

c

h

C

l

i

e

n

t

(




f

u

n

c

t

i

o

n

(

e

n

t

)




e

n

t

:

S

i

g

n

a

l

(

2

)

;




e

n

d

,




f

u

n

c

t

i

o

n

(

e

n

t

)







i

f

(

e

n

t

:

G

e

t

B

o

a

t

I

D

(

)

 

=

=

 

2

4

0

5

6

 

a

n

d

 

e

n

t

:

G

e

t

Y

(

)

 

>

 

5

0

0

)

 

t

h

e

n




r

e

t

u

r

n

 

t

r

u

e

;







r

e

t

u

r

n

 

f

a

l

s

e

;







)

;




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

F

o

r

e

a

c

h

C

l

i

e

n

t

(




f

u

n

c

t

i

o

n

(

e

n

t

)




e

n

t

:

M

o

v

e

P

C

(

9

8

,

2

3

3

7

,

4

1

8

,

-

2

2

,

-

1

)

;




e

n

d

,




f

u

n

c

t

i

o

n

(

e

n

t

)




i

f

(

e

n

t

:

G

e

t

B

o

a

t

I

D

(

)

 

=

=

 

7

7

3

 

a

n

d

 

e

n

t

:

G

e

t

Y

(

)

 

>

 

5

0

0

)

 

t

h

e

n




r

e

t

u

r

n

 

t

r

u

e

;







r

e

t

u

r

n

 

f

a

l

s

e

;







)

;





