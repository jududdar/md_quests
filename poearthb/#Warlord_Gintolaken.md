# Warlord Gintolaken

[Warlord Gintolaken](/npc/222038) is a level 77 Giant Warrior that spawns in [Plane of Earth](/zone/222).

Their primary faction is [KOS](/faction/5017).l

o

c

a

l

 

B

O

S

S

_

T

Y

P

E

S

 

=

 

{

 

2

2

2

0

3

5

,

 

2

2

2

0

3

7

,

 

2

2

2

0

3

6

,

 

2

2

2

0

0

8

,

 

2

2

2

0

0

9

,

 

2

2

2

0

1

0

 

}

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

 

s

e

c

o

n

d

s
















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

 

 

W

a

r

l

o

r

d

 

G

i

n

t

o

l

a

k

e

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



















l

o

c

a

l

 

r

a

t

i

o

 

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

H

P

R

a

t

i

o

(

)

;




i

f

 

(

 

r

a

t

i

o

 

<

 

5

0

 

o

r

 

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

 

>

 

r

a

t

i

o

 

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

G

M

M

o

v

e

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

G

u

a

r

d

P

o

i

n

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

G

u

a

r

d

P

o

i

n

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

G

u

a

r

d

P

o

i

n

t

Z

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

H

P

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

(

)

 

+

 

m

a

t

h

.

f

l

o

o

r

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

M

a

x

H

P

(

)

 

*

 

0

.

3

)

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

 

<

 

-

1

3

7

 

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

G

M

M

o

v

e

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

Z

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




*

*

W

a

r

l

o

r

d

 

G

i

n

t

o

l

a

k

e

n

*

*

 

c

l

e

a

r

s

 

h

a

t

e

 

l

i

s

t

.




*

*

W

a

r

l

o

r

d

 

G

i

n

t

o

l

a

k

e

n

 

c

a

s

t

s

:

*

*

 

[

B

a

l

a

n

c

e

 

o

f

 

t

h

e

 

N

a

m

e

l

e

s

s

]

(

/

s

p

e

l

l

/

3

2

3

0

)

 

o

n

 

t

h

e

m

s

e

l

v

e

s

.




r

e

t

u

r

n

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

0

3

3

3

3

 

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

B

O

S

S

_

T

Y

P

E

S

)

 

d

o




i

f

 

(

 

e

l

i

s

t

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




*

*

W

a

r

l

o

r

d

 

G

i

n

t

o

l

a

k

e

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




r

e

t

u

r

n

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

S

p

a

w

n

B

y

I

D

(

3

6

9

4

9

0

)

:

G

e

t

N

P

C

(

)

:

D

e

p

o

p

(

t

r

u

e

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

G

e

t

S

p

a

w

n

B

y

I

D

(

3

6

9

4

9

0

)

:

S

e

t

T

i

m

e

r

(

3

0

2

4

0

0

0

0

0

)

;


