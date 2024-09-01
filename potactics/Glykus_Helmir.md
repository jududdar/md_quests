# Glykus Helmir

[Glykus Helmir](/npc/214053) is a level 67 Wretch Warrior that spawns in [Drunder, the Fortress of Zek](/zone/214).

Their primary faction is [Gladiators of Drunder](/faction/1647).l

o

c

a

l

 

B

O

A

R

_

S

P

A

W

N

I

D

S

 

=

 

{

 

3

6

1

3

4

9

,

 

3

6

1

3

5

0

,

 

3

6

1

3

5

1

,

 

3

6

1

3

5

2

,

 

3

6

1

3

5

6

 

}

;




l

o

c

a

l

 

F

L

E

D

G

L

I

N

G

_

T

Y

P

E

 

=

 

2

1

4

0

4

0

;

 




l

o

c

a

l

 

E

N

R

A

G

E

D

_

T

Y

P

E

 

=

 

2

1

4

3

0

8

;

 




l

o

c

a

l

 

F

I

E

R

C

E

_

T

Y

P

E

 

=

 

2

1

4

2

9

6

;

 




l

o

c

a

l

 

G

R

E

A

T

E

R

_

T

Y

P

E

 

=

 

2

1

4

3

0

0

;

 




l

o

c

a

l

 

E

N

C

H

A

N

T

E

D

_

T

Y

P

E

 

=

 

2

1

4

3

0

7

;

 







l

o

c

a

l

 

b

o

a

r

s

 

=

 

{

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

B

O

A

R

_

S

P

A

W

N

I

D

S

)

 

d

o




b

o

a

r

s

[

i

d

]

 

=

 

0

;










f

u

n

c

t

i

o

n

 

E

v

o

l

v

e

B

o

a

r

(

s

p

a

w

n

I

d

)







l

o

c

a

l

 

e

n

t

i

t

y

I

d

 

=

 

b

o

a

r

s

[

s

p

a

w

n

I

d

]

;







i

f

 

(

 

e

n

t

i

t

y

I

d

 

a

n

d

 

e

n

t

i

t

y

I

d

 

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

I

D

(

e

n

t

i

t

y

I

d

)

;







i

f

 

(

 

m

o

b

 

a

n

d

 

m

o

b

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







l

o

c

a

l

 

t

y

p

e

I

d

 

=

 

m

o

b

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

;




l

o

c

a

l

 

n

e

w

T

y

p

e

;







i

f

 

(

 

t

y

p

e

I

d

 

=

=

 

F

L

E

D

G

L

I

N

G

_

T

Y

P

E

 

)

 

t

h

e

n




n

e

w

T

y

p

e

 

=

 

E

N

R

A

G

E

D

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

i

f

 

(

 

t

y

p

e

I

d

 

=

=

 

E

N

R

A

G

E

D

_

T

Y

P

E

 

)

 

t

h

e

n




n

e

w

T

y

p

e

 

=

 

F

I

E

R

C

E

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

i

f

 

(

 

t

y

p

e

I

d

 

=

=

 

F

I

E

R

C

E

_

T

Y

P

E

 

)

 

t

h

e

n




n

e

w

T

y

p

e

 

=

 

G

R

E

A

T

E

R

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

i

f

 

(

 

t

y

p

e

I

d

 

=

=

 

G

R

E

A

T

E

R

_

T

Y

P

E

 

)

 

t

h

e

n




n

e

w

T

y

p

e

 

=

 

E

N

C

H

A

N

T

E

D

_

T

Y

P

E

;










i

f

 

(

 

n

e

w

T

y

p

e

 

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

 

n

e

w

M

o

b

 

=

 

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

n

e

w

T

y

p

e

,

 

0

,

 

0

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

 

m

o

b

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




b

o

a

r

s

[

s

p

a

w

n

I

d

]

 

=

 

n

e

w

M

o

b

:

G

e

t

I

D

(

)

;




n

e

w

M

o

b

:

S

e

t

R

u

n

n

i

n

g

(

t

r

u

e

)

;




m

o

b

:

D

e

p

o

p

(

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

 

G

e

t

B

o

a

r

I

D

s

(

)




l

o

c

a

l

 

n

p

c

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

A

R

_

S

P

A

W

N

I

D

S

)

 

d

o







n

p

c

 

=

 

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

G

e

t

N

P

C

(

)

;




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

 

)

 

t

h

e

n




b

o

a

r

s

[

i

d

]

 

=

 

n

p

c

:

G

e

t

I

D

(

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

 

D

e

p

o

p

B

o

a

r

s

(

)




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

r

 

d

e

p

o

p

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




l

o

c

a

l

 

t

y

p

e

I

d

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

 

)

 

t

h

e

n




t

y

p

e

I

d

 

=

 

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




i

f

 

(

 

t

y

p

e

I

d

 

=

=

 

E

N

R

A

G

E

D

_

T

Y

P

E

 

o

r

 

t

y

p

e

I

d

 

=

=

 

F

I

E

R

C

E

_

T

Y

P

E




o

r

 

t

y

p

e

I

d

 

=

=

 

G

R

E

A

T

E

R

_

T

Y

P

E

 

o

r

 

t

y

p

e

I

d

 

=

=

 

E

N

C

H

A

N

T

E

D

_

T

Y

P

E




)

 

t

h

e

n




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

l

y

k

u

s

 

H

e

l

m

i

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




G

e

t

B

o

a

r

I

D

s

(

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

e

v

o

l

v

e

*

 

f

o

r

 

5

9

 

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

r

e

s

p

a

w

n

*

 

f

o

r

 

6

 

s

e

c

o

n

d

s




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

G

l

y

k

u

s

 

H

e

l

m

i

r

 

b

l

o

w

s

 

a

 

c

a

r

v

e

d

 

b

o

a

r

 

h

o

r

n

.

 

'

M

y

 

p

e

t

s

!

 

I

 

e

n

f

u

s

e

 

y

o

u

 

w

i

t

h

 

t

h

e

 

p

o

w

e

r

 

o

f

 

Z

e

k

.

 

 

G

r

o

w

 

a

n

d

 

b

a

t

t

l

e

 

w

i

t

h

 

G

l

y

k

u

s

!

'

*

<

/

s

p

a

n

>




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

r

e

s

p

a

w

n

*




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

o

f

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

e

v

o

l

v

e

"

 

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

E

v

o

l

v

i

n

g

 

b

o

a

r

s

"

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




l

o

c

a

l

 

s

p

a

w

n

,

 

m

o

b

;







f

o

r

 

s

p

a

w

n

I

d

,

 

e

n

t

i

t

y

I

d

 

i

n

 

p

a

i

r

s

(

b

o

a

r

s

)

 

d

o







s

p

a

w

n

 

=

 

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

s

p

a

w

n

I

d

)

;










i

f

 

(

 

n

o

t

 

s

p

a

w

n

:

G

e

t

N

P

C

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




s

p

a

w

n

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

2

0

0

0

0

0

)

;













i

f

 

(

 

e

n

t

i

t

y

I

d

 

>

 

0

 

)

 

t

h

e

n




m

o

b

 

=

 

e

l

i

s

t

:

G

e

t

M

o

b

I

D

(

e

n

t

i

t

y

I

d

)

;







i

f

 

(

 

m

o

b

 

a

n

d

 

m

o

b

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




E

v

o

l

v

e

B

o

a

r

(

s

p

a

w

n

I

d

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




l

o

c

a

l

 

t

y

p

e

I

d

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

 

)

 

t

h

e

n




t

y

p

e

I

d

 

=

 

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




i

f

 

(

 

t

y

p

e

I

d

 

=

=

 

F

L

E

D

G

L

I

N

G

_

T

Y

P

E

 

o

r

 

t

y

p

e

I

d

 

=

=

 

E

N

R

A

G

E

D

_

T

Y

P

E

 

o

r

 

t

y

p

e

I

d

 

=

=

 

F

I

E

R

C

E

_

T

Y

P

E




o

r

 

t

y

p

e

I

d

 

=

=

 

G

R

E

A

T

E

R

_

T

Y

P

E

 

o

r

 

t

y

p

e

I

d

 

=

=

 

E

N

C

H

A

N

T

E

D

_

T

Y

P

E




)

 

t

h

e

n




n

p

c

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

 

-

1

,

 

t

r

u

e

)

;
















i

f

 

(

 

n

o

t

 

e

.

s

e

l

f

:

I

s

E

n

g

a

g

e

d

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

r

e

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

 

s

p

a

w

n

I

d

,

 

e

n

t

i

t

y

I

d

 

i

n

 

p

a

i

r

s

(

b

o

a

r

s

)

 

d

o







s

p

a

w

n

 

=

 

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

s

p

a

w

n

I

d

)

;







i

f

 

(

 

e

n

t

i

t

y

I

d

 

>

 

0

 

)

 

t

h

e

n




m

o

b

 

=

 

e

l

i

s

t

:

G

e

t

M

o

b

I

D

(

e

n

t

i

t

y

I

d

)

;







i

f

 

(

 

n

o

t

 

m

o

b

 

o

r

 

n

o

t

 

m

o

b

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




s

p

a

w

n

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




b

o

a

r

s

[

s

p

a

w

n

I

d

]

 

=

 

0

;







e

l

s

e




s

p

a

w

n

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

o

f

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







i

f

 

(

 

n

o

t

 

e

.

s

e

l

f

:

I

s

E

n

g

a

g

e

d

(

)

 

)

 

t

h

e

n




D

e

p

o

p

B

o

a

r

s

(

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

 

1

 

)

 

t

h

e

n




G

e

t

B

o

a

r

I

D

s

(

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




D

e

p

o

p

B

o

a

r

s

(

)

;


