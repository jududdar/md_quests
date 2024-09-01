# Avhi Escron

[Avhi Escron](/npc/200225) is a level 70 Lepertoloth Necromancer that spawns in [The Crypt of Decay](/zone/200).

Their primary faction is [KOS](/faction/5017).l

o

c

a

l

 

R

E

A

V

E

R

_

L

O

C

S

 

=

 

{




{

 

4

1

3

,

 

1

1

5

 

}

,




{

 

3

8

7

,

 

1

2

9

 

}

,




{

 

3

8

8

,

 

1

5

3

 

}

,




{

 

4

2

0

,

 

1

5

1

 

}

,




}

;







f

u

n

c

t

i

o

n

 

S

p

a

w

n

R

e

a

v

e

r

s

(

m

o

b

,

 

n

o

E

m

o

t

e

)




f

o

r

 

i

,

 

c

o

o

r

d

s

 

i

n

 

i

p

a

i

r

s

(

R

E

A

V

E

R

_

L

O

C

S

)

 

d

o




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

2

0

0

2

5

9

,

 

0

,

 

0

,

 

c

o

o

r

d

s

[

1

]

,

 

c

o

o

r

d

s

[

2

]

,

 

-

6

0

,

 

1

2

8

)

;

 







i

f

 

(

 

n

o

t

 

n

o

E

m

o

t

e

 

)

 

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

M

e

s

s

a

g

e

C

l

o

s

e

(

m

o

b

,

 

t

r

u

e

,

 

2

0

0

,

 

0

,

 

"

M

a

n

i

a

c

a

l

 

l

a

u

g

h

t

e

r

 

e

c

h

o

e

s

 

a

r

o

u

n

d

 

t

h

e

 

r

o

o

m

 

a

s

 

t

h

e

 

a

n

c

i

e

n

t

 

d

a

r

k

 

l

i

c

h

 

u

s

e

s

 

t

h

e

 

f

r

e

s

h

l

y

 

d

e

a

d

 

b

o

d

y

 

t

o

 

s

u

m

m

o

n

 

f

o

r

t

h

 

e

v

e

n

 

m

o

r

e

 

r

e

a

n

i

m

a

t

e

d

 

r

e

a

v

e

r

s

.

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

h

a

t

e

_

l

i

s

t

(

e

)




i

f

 

(

 

n

o

t

 

e

.

j

o

i

n

e

d

 

a

n

d

 

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

(

)

 

>

 

0

 

)

 

t

h

e

n




S

p

a

w

n

R

e

a

v

e

r

s

(

e

.

s

e

l

f

)

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

1

7

0

0

 

s

e

c

o

n

d

s




S

p

a

w

n

R

e

a

v

e

r

s

(

e

.

s

e

l

f

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

i

m

e

r

(

s

)




*

*

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

T

h

e

 

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

 

o

n

c

e

 

a

g

a

i

n

 

s

a

y

i

n

g

,

 

'

B

e

t

r

a

y

e

r

 

a

n

d

 

d

e

s

e

c

r

a

t

o

r

 

o

f

 

s

t

o

r

m

s

 

I

 

c

a

l

l

 

u

p

o

n

 

y

o

u

 

t

o

 

e

n

d

 

t

h

e

 

l

i

v

e

s

 

o

f

 

t

h

e

s

e

 

f

o

o

l

s

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

B

i

s

h

o

p

 

T

o

l

u

w

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

8

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

 

8

4

,

 

*

*

x

:

*

*

 

2

5

8

)


