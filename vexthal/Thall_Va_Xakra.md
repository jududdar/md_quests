# Thall Va Xakra

[Thall Va Xakra](/npc/158136) is a level 60 Shade Warrior that spawns in [Vex Thal](/zone/158).

Their primary faction is [KOS](/faction/5017).l

o

c

a

l

 

N

O

R

T

H

_

T

V

X

_

T

Y

P

E

 

=

 

1

5

8

1

3

6

;




l

o

c

a

l

 

S

O

U

T

H

_

T

V

X

_

T

Y

P

E

 

=

 

1

5

8

4

6

5

;




l

o

c

a

l

 

N

O

R

T

H

_

V

A

_

X

A

K

R

A

1

_

S

P

A

W

N

I

D

 

=

 

3

6

5

8

5

9

;




l

o

c

a

l

 

N

O

R

T

H

_

V

A

_

X

A

K

R

A

2

_

S

P

A

W

N

I

D

 

=

 

3

6

5

5

8

2

;




l

o

c

a

l

 

S

O

U

T

H

_

V

A

_

X

A

K

R

A

1

_

S

P

A

W

N

I

D

 

=

 

3

6

6

9

6

2

;




l

o

c

a

l

 

S

O

U

T

H

_

V

A

_

X

A

K

R

A

2

_

S

P

A

W

N

I

D

 

=

 

3

6

6

4

2

9

;







l

o

c

a

l

 

L

I

N

K

_

H

A

T

E

_

C

A

P

 

=

 

5

0

0

0

;







l

o

c

a

l

 

B

A

D

_

C

O

O

R

D

S

 

=

 

{







{

 

-

2

7

0

,

 

-

1

5

7

,

	

	




-

1

0

0

0

,

 

-

1

8

1

,

	

	




-

1

0

0

0

,

 

1

0

0

0

,

	

	




}

,







{

 

-

2

7

0

,

 

5

7

3

,

	

	




-

1

0

0

0

,

 

-

6

0

3

,

	

	




-

1

0

0

0

,

 

1

0

0

0

,

	

	




}

,







{

 

-

2

7

0

,

 

-

1

5

7

,

	

	




1

8

1

,

 

1

0

0

0

,

	

	




-

1

0

0

0

,

 

1

0

0

0

,

	

	




}

,







{

 

-

2

7

0

,

 

5

7

3

,

	

	




6

0

3

,

 

1

0

0

0

,

	

	




-

1

0

0

0

,

 

1

0

0

0

,

	

	




}

,







{

 

-

5

0

0

,

 

1

0

0

0

,

	

	




-

1

0

0

0

,

 

1

0

0

0

,

	

	




1

0

0

,

 

1

0

0

0

,

	

	




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

 

B

a

d

A

r

e

a

C

h

e

c

k

(

s

e

l

f

)







l

o

c

a

l

 

h

l

 

=

 

s

e

l

f

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




l

o

c

a

l

 

c

l

i

e

n

t

s

 

=

 

{

}

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

l

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

 

)

 

t

h

e

n




t

a

b

l

e

.

i

n

s

e

r

t

(

c

l

i

e

n

t

s

,

 

e

n

t

.

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

)

;













i

f

 

(

 

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

2

6

0

 

a

n

d

 

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

 

0

 

)

 

t

h

e

n




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




s

e

l

f

:

W

i

p

e

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

 

_

,

 

c

l

i

e

n

t

 

i

n

 

i

p

a

i

r

s

(

c

l

i

e

n

t

s

)

 

d

o




i

f

 

(

 

n

o

t

 

c

l

i

e

n

t

:

G

e

t

G

M

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

B

A

D

_

C

O

O

R

D

S

)

 

d

o







i

f

 

(

 

c

l

i

e

n

t

:

G

e

t

X

(

)

 

>

 

c

o

o

r

d

s

[

1

]

 

a

n

d

 

c

l

i

e

n

t

:

G

e

t

X

(

)

 

<

 

c

o

o

r

d

s

[

2

]




a

n

d

 

c

l

i

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

 

c

o

o

r

d

s

[

3

]

 

a

n

d

 

c

l

i

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

 

<

 

c

o

o

r

d

s

[

4

]




a

n

d

 

c

l

i

e

n

t

:

G

e

t

Z

(

)

 

>

 

c

o

o

r

d

s

[

5

]

 

a

n

d

 

c

l

i

e

n

t

:

G

e

t

Z

(

)

 

<

 

c

o

o

r

d

s

[

6

]




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

t

o

p

 

C

h

e

a

t

i

n

g

]

(

/

n

p

c

/

1

5

8

4

8

0

)




r

e

t

u

r

n

;






















f

u

n

c

t

i

o

n

 

A

g

g

r

o

L

i

n

k

(

b

o

s

s

,

 

g

u

a

r

d

I

d

)




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

 

b

o

s

s

T

o

p

H

a

t

e

r

 

=

 

b

o

s

s

:

G

e

t

H

a

t

e

T

o

p

(

)

;




l

o

c

a

l

 

b

o

s

s

T

o

p

H

a

t

e

 

=

 

b

o

s

s

:

G

e

t

H

a

t

e

A

m

o

u

n

t

(

b

o

s

s

T

o

p

H

a

t

e

r

,

 

f

a

l

s

e

)

;




l

o

c

a

l

 

c

a

p

p

e

d

H

a

t

e

 

=

 

b

o

s

s

T

o

p

H

a

t

e

;




l

o

c

a

l

 

t

o

p

H

a

t

e

r

G

u

a

r

d

H

a

t

e

;




i

f

 

(

 

b

o

s

s

T

o

p

H

a

t

e

 

>

 

L

I

N

K

_

H

A

T

E

_

C

A

P

 

)

 

t

h

e

n




c

a

p

p

e

d

H

a

t

e

 

=

 

L

I

N

K

_

H

A

T

E

_

C

A

P

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

 

=

=

 

g

u

a

r

d

I

d

 

)

 

t

h

e

n







i

f

 

(

 

b

o

s

s

T

o

p

H

a

t

e

r

 

)

 

t

h

e

n




t

o

p

H

a

t

e

r

G

u

a

r

d

H

a

t

e

 

=

 

n

p

c

:

G

e

t

H

a

t

e

A

m

o

u

n

t

(

b

o

s

s

T

o

p

H

a

t

e

r

,

 

f

a

l

s

e

)

;







i

f

 

(

 

t

o

p

H

a

t

e

r

G

u

a

r

d

H

a

t

e

 

<

 

c

a

p

p

e

d

H

a

t

e

 

)

 

t

h

e

n




n

p

c

:

S

e

t

H

a

t

e

(

b

o

s

s

T

o

p

H

a

t

e

r

,

 

c

a

p

p

e

d

H

a

t

e

)

;










r

e

t

u

r

n

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

h

a

l

l

 

V

a

 

X

a

k

r

a

 

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

a

g

g

r

o

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

2

6

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

a

t

_

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




B

a

d

A

r

e

a

C

h

e

c

k

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

a

g

g

r

o

c

h

e

c

k

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

c

h

e

a

t

_

c

h

e

c

k

*




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

5

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

a

g

g

r

o

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




l

o

c

a

l

 

s

e

l

f

I

d

 

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

 

m

o

b

;







i

f

 

(

 

s

e

l

f

I

d

 

=

=

 

N

O

R

T

H

_

T

V

X

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




A

g

g

r

o

L

i

n

k

(

e

.

s

e

l

f

,

 

N

O

R

T

H

_

V

A

_

X

A

K

R

A

1

_

S

P

A

W

N

I

D

)

;




A

g

g

r

o

L

i

n

k

(

e

.

s

e

l

f

,

 

N

O

R

T

H

_

V

A

_

X

A

K

R

A

2

_

S

P

A

W

N

I

D

)

;




e

l

s

e

i

f

 

(

 

s

e

l

f

I

d

 

=

=

 

S

O

U

T

H

_

T

V

X

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




A

g

g

r

o

L

i

n

k

(

e

.

s

e

l

f

,

 

S

O

U

T

H

_

V

A

_

X

A

K

R

A

1

_

S

P

A

W

N

I

D

)

;




A

g

g

r

o

L

i

n

k

(

e

.

s

e

l

f

,

 

S

O

U

T

H

_

V

A

_

X

A

K

R

A

2

_

S

P

A

W

N

I

D

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

a

t

_

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

2

6

0

 

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

R

a

t

i

o

(

)

 

>

 

9

5

 

)

 

t

h

e

n




B

a

d

A

r

e

a

C

h

e

c

k

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








