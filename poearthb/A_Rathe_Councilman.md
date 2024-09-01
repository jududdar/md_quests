# A Rathe Councilman

[A Rathe Councilman](/npc/222003) is a level 68 The Rathe Warrior that spawns in [Plane of Earth](/zone/222).

Their primary faction is [KOS](/faction/5017).l

o

c

a

l

 

M

E

Z

A

B

L

E

_

T

Y

P

E

 

=

 

2

2

2

0

0

3

;




l

o

c

a

l

 

U

N

M

E

Z

A

B

L

E

_

T

Y

P

E

 

=

 

2

2

2

0

3

9

;




l

o

c

a

l

 

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

9

3

7

7

,

 

3

6

9

3

8

0

,

 

3

6

9

3

8

2

,

 

3

6

9

3

8

4

,

 

3

6

9

3

8

6

,

 

3

6

9

3

8

7

,

 

3

6

9

3

7

6

,

 

3

6

9

3

7

8

,

 

3

6

9

3

7

9

,

 

3

6

9

3

8

1

,

 

3

6

9

3

8

3

,

 

3

6

9

3

8

5

 

}

;




l

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

3

8

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

 




l

o

c

a

l

 

T

E

L

E

P

O

R

T

_

B

O

U

N

D

S

 

=

 

{




{

 

n

 

=

 

9

5

7

,

 

s

 

=

 

8

6

1

,

 

w

 

=

 

2

2

4

8

,

 

e

 

=

 

1

9

2

5

 

}

,




{

 

n

 

=

 

5

6

4

,

 

s

 

=

 

2

3

8

,

 

w

 

=

 

2

6

0

0

,

 

e

 

=

 

2

5

2

1

 

}

,




{

 

n

 

=

 

5

6

9

,

 

s

 

=

 

2

3

6

,

 

w

 

=

 

1

5

9

5

,

 

e

 

=

 

1

5

1

1

 

}

,




{

 

n

 

=

 

-

5

5

,

 

s

 

=

 

-

1

3

2

,

 

w

 

=

 

2

1

8

0

,

 

e

 

=

 

1

8

5

5

 

}

,




}

;




l

o

c

a

l

 

T

H

R

E

S

H

O

L

D

S

 

=

 

{

 

7

5

,

 

5

0

,

 

2

5

,

 

1

1

 

}

;




l

o

c

a

l

 

M

I

N

_

H

I

T

S

 

=

 

{

 

6

2

3

,

 

5

3

3

,

 

4

4

4

,

 

3

5

4

,

 

1

8

5

 

}

;




l

o

c

a

l

 

M

A

X

_

H

I

T

S

 

=

 

{

 

2

9

6

4

,

 

2

4

9

8

,

 

2

0

3

2

,

 

1

5

6

6

,

 

8

5

0

 

}

;







l

o

c

a

l

 

k

i

l

l

e

d

 

=

 

{

}

;




l

o

c

a

l

 

s

t

a

t

e

 

=

 

{

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

 

T

e

l

e

p

o

r

t

C

l

i

e

n

t

(

c

)




l

o

c

a

l

 

x

 

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

 

4

)

;




l

o

c

a

l

 

r

o

l

l

X

,

 

r

o

l

l

Y

;







r

o

l

l

X

 

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

T

E

L

E

P

O

R

T

_

B

O

U

N

D

S

[

x

]

.

e

,

 

T

E

L

E

P

O

R

T

_

B

O

U

N

D

S

[

x

]

.

w

)

;




r

o

l

l

Y

 

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

T

E

L

E

P

O

R

T

_

B

O

U

N

D

S

[

x

]

.

s

,

 

T

E

L

E

P

O

R

T

_

B

O

U

N

D

S

[

x

]

.

n

)

;







c

:

M

o

v

e

P

C

(

2

2

2

,

 

r

o

l

l

X

,

 

r

o

l

l

Y

,

 

-

2

5

5

,

 

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

0

,

 

5

1

0

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

 

m

y

S

p

a

w

n

I

D

 

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

;




k

i

l

l

e

d

[

m

y

S

p

a

w

n

I

D

]

 

=

 

n

i

l

;




s

t

a

t

e

[

m

y

S

p

a

w

n

I

D

]

 

=

 

n

i

l

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




i

f

 

(

 

i

d

 

~

=

 

m

y

S

p

a

w

n

I

D

 

)

 

t

h

e

n




i

f

 

(

 

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




r

e

t

u

r

n

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




e

q

.

u

p

d

a

t

e

_

s

p

a

w

n

_

t

i

m

e

r

(

i

d

,

 

1

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

"

F

u

l

l

 

c

o

u

n

c

i

l

 

r

e

p

o

p

"

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

 

R

a

t

h

e

 

C

o

u

n

c

i

l

m

a

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

t

e

l

e

p

o

r

t

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

 

M

E

Z

A

B

L

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

_

m

e

z

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

t

e

l

e

p

o

r

t

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

c

k

_

m

e

z

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

c

k

_

u

n

m

e

z

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

t

e

n

_

m

i

n

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







l

o

c

a

l

 

m

y

S

p

a

w

n

I

D

 

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

;




l

o

c

a

l

 

m

y

S

t

a

t

e

 

=

 

s

t

a

t

e

[

m

y

S

p

a

w

n

I

D

]

 

o

r

 

1

;




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







i

f

 

(

 

m

y

S

t

a

t

e

 

>

 

1

 

a

n

d

 

r

a

t

i

o

 

>

 

T

H

R

E

S

H

O

L

D

S

[

1

]

 

)

 

t

h

e

n




s

t

a

t

e

[

m

y

S

p

a

w

n

I

D

]

 

=

 

1

;




e

.

s

e

l

f

:

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

m

i

n

_

h

i

t

"

,

 

t

o

s

t

r

i

n

g

(

M

I

N

_

H

I

T

S

[

1

]

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

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

m

a

x

_

h

i

t

"

,

 

t

o

s

t

r

i

n

g

(

M

A

X

_

H

I

T

S

[

1

]

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

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

a

c

c

u

r

a

c

y

"

,

 

t

o

s

t

r

i

n

g

(

3

5

0

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

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

a

t

k

"

,

 

t

o

s

t

r

i

n

g

(

3

0

)

)

;




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

q

.

d

e

b

u

g

(

"

C

o

u

n

c

i

l

m

a

n

 

c

o

m

b

a

t

 

s

t

a

t

s

 

r

e

s

e

t

"

,

 

3

)

;




r

e

t

u

r

n

;







e

l

s

e

i

f

 

(

 

m

y

S

t

a

t

e

 

=

=

 

1

 

a

n

d

 

r

a

t

i

o

 

>

 

T

H

R

E

S

H

O

L

D

S

[

1

]

 

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

 

m

y

S

t

a

t

e

 

>

 

#

T

H

R

E

S

H

O

L

D

S

 

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

;




e

l

s

e

i

f

 

(

 

r

a

t

i

o

 

<

 

T

H

R

E

S

H

O

L

D

S

[

m

y

S

t

a

t

e

]

 

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




r

e

t

u

r

n

;










]

]










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




r

e

t

u

r

n

;










m

y

S

t

a

t

e

 

=

 

m

y

S

t

a

t

e

 

+

 

1

;




s

t

a

t

e

[

m

y

S

p

a

w

n

I

D

]

 

=

 

m

y

S

t

a

t

e

;




e

.

s

e

l

f

:

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

m

i

n

_

h

i

t

"

,

 

t

o

s

t

r

i

n

g

(

M

I

N

_

H

I

T

S

[

m

y

S

t

a

t

e

]

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

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

m

a

x

_

h

i

t

"

,

 

t

o

s

t

r

i

n

g

(

M

A

X

_

H

I

T

S

[

m

y

S

t

a

t

e

]

)

)

;




i

f

 

(

 

m

y

S

t

a

t

e

 

=

=

 

5

 

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

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

a

c

c

u

r

a

c

y

"

,

 

t

o

s

t

r

i

n

g

(

0

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

M

o

d

i

f

y

N

P

C

S

t

a

t

(

"

a

t

k

"

,

 

t

o

s

t

r

i

n

g

(

0

)

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




e

q

.

d

e

b

u

g

(

 

s

t

r

i

n

g

.

f

o

r

m

a

t

(

"

P

o

E

a

r

t

h

B

 

R

a

t

h

e

 

C

o

u

n

c

i

l

m

a

n

 

d

i

s

e

m

p

o

w

e

r

e

d

;

 

T

a

n

k

:

 

%

s

 

<

%

s

>

"

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

T

a

r

g

e

t

(

)

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

T

a

r

g

e

t

(

)

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

G

e

t

G

u

i

l

d

N

a

m

e

(

)

)

 

)

;










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

 

g

r

o

u

n

d

 

s

h

u

d

d

e

r

s

 

b

e

n

e

a

t

h

 

y

o

u

r

 

f

e

e

t

 

a

s

 

f

l

e

c

k

s

 

o

f

 

d

i

r

t

 

a

n

d

 

s

t

o

n

e

 

f

a

l

l

 

a

w

a

y

 

f

r

o

m

 

o

n

e

 

o

f

 

t

h

e

 

R

a

t

h

e

.

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

t

e

l

e

p

o

r

t

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

I

s

M

e

z

z

e

d

(

)

 

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

 

1

1

 

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

;










l

o

c

a

l

 

h

l

 

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

C

a

l

c

u

l

a

t

e

D

i

s

t

a

n

c

e

(

e

n

t

.

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

,

 

e

n

t

.

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

,

 

e

n

t

.

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

 

#

c

l

i

e

n

t

s

 

>

 

0

 

)

 

t

h

e

n




T

e

l

e

p

o

r

t

C

l

i

e

n

t

(

 

c

l

i

e

n

t

s

[

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

 

#

c

l

i

e

n

t

s

)

]

 

)

;







]

]




l

o

c

a

l

 

c

 

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

a

t

e

R

a

n

d

o

m

C

l

i

e

n

t

(

6

0

0

)

;




i

f

 

(

 

c

 

a

n

d

 

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




T

e

l

e

p

o

r

t

C

l

i

e

n

t

(

c

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

t

e

n

_

m

i

n

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

I

s

M

e

z

z

e

d

(

)

 

)

 

t

h

e

n




*

*

A

 

R

a

t

h

e

 

C

o

u

n

c

i

l

m

a

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

M

e

z

z

e

d

 

C

o

u

n

c

i

l

m

a

n

 

h

a

t

e

 

l

i

s

t

 

w

i

p

e

d

"

,

 

3

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

_

m

e

z

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

I

s

M

e

z

z

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

t

e

n

_

m

i

n

*

 

f

o

r

 

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

_

u

n

m

e

z

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

_

u

n

m

e

z

"

 

)

 

t

h

e

n







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

M

e

z

z

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

t

e

n

_

m

i

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

c

h

e

c

k

_

m

e

z

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

 

S

i

g

n

a

l

s




k

i

l

l

e

d

[

e

.

s

i

g

n

a

l

]

 

=

 

1

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










l

o

c

a

l

 

m

y

S

p

a

w

n

I

D

 

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

;




k

i

l

l

e

d

[

m

y

S

p

a

w

n

I

D

]

 

=

 

1

;




l

o

c

a

l

 

m

y

T

y

p

e

 

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










i

f

 

(

 

m

y

T

y

p

e

 

=

=

 

U

N

M

E

Z

A

B

L

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

M

E

Z

A

B

L

E

_

T

Y

P

E

,

 

m

y

S

p

a

w

n

I

D

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

i

g

n

a

l

(

U

N

M

E

Z

A

B

L

E

_

T

Y

P

E

,

 

m

y

S

p

a

w

n

I

D

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




i

f

 

(

 

n

o

t

 

k

i

l

l

e

d

[

i

d

]

 

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




i

f

 

(

 

n

o

t

 

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

M

E

Z

A

B

L

E

_

T

Y

P

E

)

 

a

n

d

 

n

o

t

 

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

U

N

M

E

Z

A

B

L

E

_

T

Y

P

E

)

 

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

T

h

e

 

l

a

s

t

 

o

f

 

t

h

e

 

c

o

u

n

c

i

l

 

f

a

l

l

s

 

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

 

a

l

l

 

s

i

g

n

s

 

o

f

 

l

i

f

e

 

g

o

n

e

.

 

 

S

u

d

d

e

n

l

y

 

t

w

e

l

v

e

 

v

o

i

c

e

s

 

a

r

e

 

h

e

a

r

d

 

c

h

a

n

t

i

n

g

 

a

 

m

y

s

t

i

c

a

l

 

s

p

e

l

l

 

s

a

y

i

n

g

,

 

'

T

i

m

e

 

c

o

m

e

s

 

a

n

d

 

t

i

m

e

 

p

a

s

s

e

s

 

f

o

r

 

t

h

e

 

s

t

o

n

e

 

i

s

 

f

o

r

e

v

e

r

.

 

 

N

o

w

 

w

e

 

c

a

l

l

 

u

p

o

n

 

o

u

r

 

c

o

l

l

e

c

t

i

v

e

 

p

o

w

e

r

 

t

o

 

d

e

f

e

n

d

 

o

u

r

 

s

t

r

o

n

g

h

o

l

d

!

'

 

 

T

h

e

 

c

h

a

n

t

i

n

g

 

t

h

e

n

 

s

t

o

p

s

 

a

n

d

 

a

 

d

e

e

p

 

t

h

r

o

a

t

e

d

 

p

r

i

m

a

l

 

s

c

r

e

a

m

 

i

s

 

h

e

a

r

d

 

a

s

 

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

 

t

w

e

l

v

e

 

c

o

m

e

s

 

t

o

g

e

t

h

e

r

 

a

s

 

o

n

e

.

 

 

T

h

e

 

A

v

a

t

a

r

 

o

f

 

E

a

r

t

h

 

h

a

s

 

b

e

e

n

 

s

u

m

m

o

n

e

d

 

t

o

 

d

e

f

e

n

d

 

R

a

g

r

a

x

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

A

v

a

t

a

r

 

o

f

 

E

a

r

t

h

]

(

/

n

p

c

/

2

2

2

0

4

0

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

 

4

1

0

,

 

*

*

x

:

*

*

 

2

0

5

0

)







l

o

c

a

l

 

v

a

r

i

a

n

c

e

 

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

 

1

4

4

0

)

;




l

o

c

a

l

 

t

 

=

 

(

6

0

 

*

 

6

0

 

+

 

v

a

r

i

a

n

c

e

)

 

*

 

6

0

;

 




f

o

r

 

i

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




e

q

.

u

p

d

a

t

e

_

s

p

a

w

n

_

t

i

m

e

r

(

i

d

,

 

t

*

1

0

0

0

)

;








