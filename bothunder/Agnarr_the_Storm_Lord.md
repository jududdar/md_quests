# Agnarr the Storm Lord

[Agnarr the Storm Lord](/npc/209026) is a level 75 Karana Warrior that spawns in [Bastion of Thunder](/zone/209).

Their primary faction is [Agnarr](/faction/1621).l

o

c

a

l

 

K

A

R

A

N

A

_

T

Y

P

E

 

=

 

2

0

9

1

3

6

;




l

o

c

a

l

 

J

O

L

U

R

_

T

Y

P

E

 

=

 

2

0

9

1

4

7

;

 




l

o

c

a

l

 

E

K

I

L

_

T

Y

P

E

 

=

 

2

0

9

1

4

2

;

 




l

o

c

a

l

 

O

L

J

I

N

_

T

Y

P

E

 

=

 

2

0

9

1

4

8

;

 




l

o

c

a

l

 

H

I

B

D

I

N

_

T

Y

P

E

 

=

 

2

0

9

1

4

6

;

 







l

o

c

a

l

 

A

D

D

_

T

Y

P

E

S

 

=

 

{




[

J

O

L

U

R

_

T

Y

P

E

]

 

=

 

1

,




[

E

K

I

L

_

T

Y

P

E

]

 

=

 

1

,




[

O

L

J

I

N

_

T

Y

P

E

]

 

=

 

1

,




[

H

I

B

D

I

N

_

T

Y

P

E

]

 

=

 

1

,




[

2

0

9

1

2

4

]

 

=

 

1

,

 




[

2

0

9

1

2

3

]

 

=

 

1

,

 




[

2

0

9

1

2

5

]

 

=

 

1

,

 




[

2

0

9

1

3

0

]

 

=

 

1

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

G

i

a

n

t

(

i

d

)




e

q

.

u

n

i

q

u

e

_

s

p

a

w

n

(

i

d

,

 

0

,

 

0

,

 

-

1

0

7

0

,

 

-

1

7

3

9

,

 

2

2

5

7

,

 

6

4

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

 

 

A

g

n

a

r

r

 

t

h

e

 

S

t

o

r

m

 

L

o

r

d

 

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

A

g

n

a

r

r

 

t

h

e

 

S

t

o

r

m

 

L

o

r

d

 

s

a

y

s

 

'

F

o

o

l

!

 

T

h

i

s

 

i

s

 

t

h

e

 

r

e

a

l

m

 

o

f

 

t

h

e

 

S

t

o

r

m

 

G

i

a

n

t

s

 

n

o

w

,

 

a

n

d

 

y

o

u

 

h

o

p

e

 

t

o

 

d

e

f

e

a

t

 

m

e

 

h

e

r

e

?

'

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

p

o

r

t

a

l

s

*

 

f

o

r

 

1

2

0

 

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

l

i

n

k

*

 

f

o

r

 

4

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

H

P

R

a

t

i

o

(

)

 

>

 

9

6

 

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

7

5

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

s

p

a

w

n

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

p

o

r

t

a

l

s

*




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

l

i

n

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

l

i

n

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

Z

(

)

 

<

 

2

2

0

0

 

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

 

A

D

D

_

T

Y

P

E

S

[

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

]

 

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

T

a

r

g

e

t

(

)

 

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

T

a

r

g

e

t

(

)

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




n

p

c

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

,

 

1

0

0

)

;







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

Z

(

)

 

<

 

2

2

0

0

 

)

 

t

h

e

n




n

p

c

:

G

M

M

o

v

e

(

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

Z

(

)

,

 

0

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

p

o

r

t

a

l

s

"

 

)

 

t

h

e

n




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

A

g

n

a

r

r

 

s

t

r

i

k

e

s

 

h

i

s

 

s

t

a

f

f

 

t

o

 

t

h

e

 

g

r

o

u

n

d

,

 

c

a

u

s

i

n

g

 

g

r

e

a

t

 

r

i

p

p

l

e

s

 

o

f

 

e

n

e

r

g

y

 

t

o

 

r

a

g

e

 

a

c

r

o

s

s

 

t

h

e

 

r

o

o

m

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

A

 

s

t

o

r

m

 

p

o

r

t

a

l

]

(

/

n

p

c

/

2

0

9

0

3

4

)







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

 

2

5

 

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

p

o

r

t

a

l

s

*

 

f

o

r

 

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

l

s

e

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

p

o

r

t

a

l

s

*

 

f

o

r

 

9

0

 

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

s

p

a

w

n

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




S

p

a

w

n

G

i

a

n

t

(

J

O

L

U

R

_

T

Y

P

E

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

 

7

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

G

i

a

n

t

(

E

K

I

L

_

T

Y

P

E

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

2

5

)

;




S

p

a

w

n

G

i

a

n

t

(

O

L

J

I

N

_

T

Y

P

E

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

 

2

5

 

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

G

i

a

n

t

(

H

I

B

D

I

N

_

T

Y

P

E

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

K

A

R

A

N

A

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

 

-

4

7

7

,

 

-

1

7

5

8

,

 

2

3

5

5

,

 

1

9

2

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

K

A

R

A

N

A

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

 


