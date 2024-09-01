# Terris Thule

[Terris Thule](/npc/204483) is a level 1 Terris Thule Warrior that spawns in [The Lair of Terris Thule](/zone/221).











l

o

c

a

l

 

P

L

A

N

A

R

_

P

R

O

J

E

C

T

I

O

N

_

T

Y

P

E

 

=

 

2

2

1

0

4

2

;




l

o

c

a

l

 

D

E

F

I

L

E

R

_

S

M

A

L

L

_

T

Y

P

E

 

=

 

2

2

1

0

4

5

;




l

o

c

a

l

 

D

E

F

I

L

E

R

_

L

A

R

G

E

_

T

Y

P

E

 

=

 

2

2

1

0

4

4

;




l

o

c

a

l

 

G

A

R

G

_

T

Y

P

E

 

=

 

2

2

1

0

4

3

;




l

o

c

a

l

 

G

A

R

G

_

S

P

A

W

N

_

I

D

S

 

=

 

{

 

3

6

5

3

9

7

,

 

3

6

6

0

5

3

,

 

3

6

6

1

7

6

,

 

3

6

7

2

3

2

 

}

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

s

p

a

w

n

2

(

P

L

A

N

A

R

_

P

R

O

J

E

C

T

I

O

N

_

T

Y

P

E

,

 

0

,

 

0

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

)

;




e

q

.

s

i

g

n

a

l

(

P

L

A

N

A

R

_

P

R

O

J

E

C

T

I

O

N

_

T

Y

P

E

,

 

e

.

k

i

l

l

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




e

q

.

s

e

t

_

n

e

x

t

_

h

p

_

e

v

e

n

t

(

9

5

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

 

S

p

a

w

n

D

e

f

i

l

e

r

s

(

m

o

b

)




l

o

c

a

l

 

n

u

m

S

p

a

w

n

s

 

=

 

0

;




l

o

c

a

l

 

h

a

t

e

L

i

s

t

 

=

 

m

o

b

:

G

e

t

H

a

t

e

L

i

s

t

(

)

;







f

o

r

 

e

n

t

 

i

n

 

h

a

t

e

L

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

 

e

n

t

.

e

n

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

 

a

n

d

 

e

n

t

.

d

a

m

a

g

e

 

>

 

0

 

)

 

t

h

e

n




n

u

m

S

p

a

w

n

s

 

=

 

n

u

m

S

p

a

w

n

s

 

+

 

1

;













l

o

c

a

l

 

t

;




f

o

r

 

i

 

=

 

1

,

 

n

u

m

S

p

a

w

n

s

 

d

o




t

 

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

 

2

)

;




i

f

 

(

 

t

 

=

=

 

1

 

)

 

t

h

e

n




t

 

=

 

D

E

F

I

L

E

R

_

S

M

A

L

L

_

T

Y

P

E

;




e

l

s

e




t

 

=

 

D

E

F

I

L

E

R

_

L

A

R

G

E

_

T

Y

P

E

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

t

,

 

0

,

 

0

,

 

-

1

6

6

1

,

 

-

1

6

8

,

 

1

4

0

,

 

0

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

p

(

e

)







i

f

 

(

 

e

.

h

p

_

e

v

e

n

t

 

=

=

 

9

5

 

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

,

 

2

5

0

,

 

0

,

 

"

T

h

e

 

s

o

u

n

d

 

o

f

 

a

 

t

h

o

u

s

a

n

d

 

t

e

r

r

i

f

i

e

d

 

s

c

r

e

a

m

s

 

f

i

l

l

s

 

y

o

u

r

 

h

e

a

d

.

 

 

Y

o

u

 

f

e

e

l

 

y

o

u

r

s

e

l

f

 

b

e

c

o

m

i

n

g

 

a

 

p

a

r

t

 

o

f

 

t

h

e

 

f

a

b

r

i

c

 

o

f

 

t

h

i

s

 

n

i

g

h

t

m

a

r

e

 

r

e

a

l

m

.

"

)

;




e

q

.

s

e

t

_

n

e

x

t

_

h

p

_

e

v

e

n

t

(

7

9

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

h

p

_

e

v

e

n

t

 

=

=

 

7

9

 

)

 

t

h

e

n




e

q

.

s

e

t

_

n

e

x

t

_

h

p

_

e

v

e

n

t

(

6

9

)

;




S

p

a

w

n

D

e

f

i

l

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







e

l

s

e

i

f

 

(

 

e

.

h

p

_

e

v

e

n

t

 

=

=

 

6

9

 

)

 

t

h

e

n




e

q

.

s

e

t

_

n

e

x

t

_

h

p

_

e

v

e

n

t

(

5

0

)

;




S

p

a

w

n

D

e

f

i

l

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







e

l

s

e

i

f

 

(

 

e

.

h

p

_

e

v

e

n

t

 

=

=

 

5

0

 

)

 

t

h

e

n




e

q

.

s

e

t

_

n

e

x

t

_

h

p

_

e

v

e

n

t

(

4

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

,

 

2

5

0

,

 

0

,

 

"

A

s

 

i

f

 

i

n

 

a

 

w

a

k

i

n

g

 

n

i

g

h

t

m

a

r

e

,

 

y

o

u

 

f

e

e

l

 

y

o

u

r

 

m

o

v

e

m

e

n

t

s

 

s

l

o

w

 

a

n

d

 

y

o

u

r

 

a

r

m

s

 

b

e

g

i

n

 

t

o

 

f

a

i

l

 

y

o

u

.

 

 

E

a

c

h

 

s

w

i

n

g

 

o

f

 

y

o

u

r

 

w

e

a

p

o

n

 

f

e

e

l

s

 

a

s

 

i

f

 

i

t

 

w

i

l

l

 

m

i

s

s

 

i

t

s

 

m

a

r

k

.

 

 

 

E

v

e

n

 

y

o

u

r

 

l

e

g

s

 

b

e

g

i

n

 

t

o

 

f

a

i

l

 

y

o

u

,

 

a

s

 

y

o

u

 

f

a

l

l

 

d

e

e

p

e

r

 

i

n

t

o

 

t

h

e

 

d

r

e

a

m

l

i

k

e

 

s

t

a

t

e

!

"

)

;




*

*

T

e

r

r

i

s

 

T

h

u

l

e

 

c

a

s

t

s

:

*

*

 

[

D

i

r

e

p

t

i

o

n

 

o

f

 

D

r

e

a

m

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

1

5

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







e

l

s

e

i

f

 

(

 

e

.

h

p

_

e

v

e

n

t

 

=

=

 

4

0

 

)

 

t

h

e

n




*

*

T

e

r

r

i

s

 

T

h

u

l

e

 

s

h

o

u

t

s

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

d

a

n

g

e

r

"

>

Y

o

u

 

w

i

l

l

 

n

o

t

 

e

s

c

a

p

e

 

m

y

 

r

e

a

l

m

 

s

o

 

e

a

s

i

l

y

!

<

/

s

p

a

n

>




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

,

 

2

5

0

,

 

0

,

 

"

T

h

e

 

a

i

r

 

g

r

o

w

s

 

t

h

i

c

k

 

w

i

t

h

 

t

h

e

 

s

m

e

l

l

 

o

f

 

b

u

r

n

i

n

g

 

m

a

n

a

.

 

 

A

 

r

u

m

b

l

i

n

g

 

s

o

u

n

d

 

d

r

a

w

s

 

y

o

u

r

 

a

t

t

e

n

t

i

o

n

 

t

o

 

t

h

e

 

m

a

s

s

i

v

e

 

s

t

a

t

u

e

s

 

t

h

a

t

 

r

e

s

t

 

a

b

o

v

e

 

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

 

m

o

n

o

l

i

t

h

s

.

 

 

T

h

e

 

s

t

a

t

u

e

s

 

b

e

g

i

n

 

t

o

 

c

r

u

m

b

l

e

,

 

a

s

 

t

h

e

y

 

s

h

i

f

t

 

t

h

e

i

r

 

a

t

t

e

n

t

i

o

n

 

f

r

o

m

 

t

h

e

 

h

e

a

v

e

n

s

 

t

o

 

y

o

u

!

"

)

;







l

o

c

a

l

 

n

p

c

L

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

L

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

L

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

.

v

a

l

i

d

 

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

 

)

 

t

h

e

n







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

G

A

R

G

_

S

P

A

W

N

_

I

D

S

)

 

d

o




i

f

 

(

 

i

d

 

=

=

 

n

p

c

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

G

A

R

G

_

T

Y

P

E

,

 

0

,

 

0

,

 

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

,

 

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

,

 

n

p

c

:

G

e

t

Z

(

)

,

 

n

p

c

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

t

r

u

e

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

 

 

T

e

r

r

i

s

 

T

h

u

l

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

b

o

u

n

d

s

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




e

l

s

e




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

 

3

 

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

b

o

u

n

d

s

c

h

e

c

k

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

 

=

=

 

1

0

0

 

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

c

h

e

c

k

h

p

*




e

q

.

s

e

t

_

n

e

x

t

_

h

p

_

e

v

e

n

t

(

9

5

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

G

A

R

G

_

S

P

A

W

N

_

I

D

S

)

 

d

o




e

l

i

s

t

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

i

d

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

1

)

;







e

q

.

d

e

p

o

p

_

a

l

l

(

G

A

R

G

_

T

Y

P

E

)

;




]

]










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

b

o

u

n

d

s

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

 

>

 

-

1

5

8

0

 

o

r

 

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

2

0

9

0

 

o

r

 

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

 

>

 

2

5

0

 

o

r

 

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

 

<

 

-

2

8

0

 

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

,

 

2

0

0

,

 

0

,

 

"

T

e

r

r

i

s

 

T

h

u

l

e

 

d

i

s

a

p

p

e

a

r

s

 

i

n

t

o

 

t

h

e

 

e

t

h

e

r

 

a

n

d

 

r

e

f

o

r

m

s

 

a

t

 

t

h

e

 

c

e

n

t

e

r

 

o

f

 

h

e

r

 

c

h

a

m

b

e

r

,

 

c

l

e

a

n

s

e

d

 

o

f

 

y

o

u

r

 

m

a

g

i

c

!

"

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

T

e

r

r

i

s

 

T

h

u

l

e

 

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








