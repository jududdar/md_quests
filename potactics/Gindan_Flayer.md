# Gindan Flayer

[Gindan Flayer](/npc/214084) is a level 68 Rallos Zek Minion Warrior that spawns in [Drunder, the Fortress of Zek](/zone/214).

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

 

F

l

a

y

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

1

4

0

8

4

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

 

F

l

a

y

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

1

4

0

8

4

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

 

F

l

a

y

e

r

 

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

 

F

l

a

y

e

r

 

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

 

F

l

a

y

e

r

 

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

Z

(

)

 

>

 

1

5

6

 

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

X

(

)

 

>

 

0

 

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

n

d

 

t

.

v

a

l

i

d

 

a

n

d

 

t

:

G

e

t

Z

(

)

 

<

 

1

0

0

 

a

n

d

 

t

:

G

e

t

X

(

)

 

<

 

6

0

0

 

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

y

p

e

s

 

=

 

{

 

2

1

4

3

1

3

,

 

2

1

4

3

2

0

,

 

2

1

4

3

1

1

 

}

;

	




f

o

r

 

_

,

 

i

d

 

i

n

 

i

p

a

i

r

s

(

t

y

p

e

s

)

 

d

o




i

f

 

(

 

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

i

d

)

 

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

 

m

o

b

 

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

i

d

)

;




e

.

s

e

l

f

:

G

M

M

o

v

e

(

m

o

b

:

G

e

t

X

(

)

,

 

m

o

b

:

G

e

t

Y

(

)

,

 

m

o

b

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




i

f

 

(

 

t

:

I

s

C

l

i

e

n

t

(

)

 

)

 

t

h

e

n




t

:

C

a

s

t

T

o

C

l

i

e

n

t

(

)

:

M

o

v

e

P

C

(

2

1

4

,

 

m

o

b

:

G

e

t

X

(

)

,

 

m

o

b

:

G

e

t

Y

(

)

,

 

m

o

b

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







b

r

e

a

k

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

 

S

i

g

n

a

l

s







i

f

 

(

 

e

.

s

i

g

n

a

l

 

=

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

I

D

(

)

 

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





