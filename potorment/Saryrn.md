# Saryrn

[Saryrn](/npc/207001) is a level 70 Saryrn Warrior that spawns in [Torment, the Plane of Pain](/zone/207).

Their primary faction is [Servants of Saryrn](/faction/1624).l

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

0

7

3

1

7

;




l

o

c

a

l

 

S

O

R

R

O

W

S

O

N

G

_

T

Y

P

E

I

D

 

=

 

2

0

7

0

5

2

;




l

o

c

a

l

 

S

O

R

R

O

W

S

O

N

G

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

4

6

7

6

1

;







l

o

c

a

l

 

H

P

_

E

V

E

N

T

S

 

=

 

{

 

9

9

,

 

9

0

,

 

8

0

,

 

7

0

,

 

6

0

,

 

5

0

,

 

4

0

,

 

3

0

,

 

2

5

,

 

2

0

,

 

1

0

 

}

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

_

L

O

C

S

 

=

 

{




{

 

7

8

,

 

-

6

9

,

 

5

0

5

.

5

,

 

1

2

8

 

}

,




{

 

7

9

,

 

-

7

,

 

4

5

5

.

5

,

 

1

2

8

 

}

,




{

 

2

1

,

 

-

3

7

,

 

4

5

5

.

5

,

 

1

7

2

 

}

,




{

 

-

4

9

,

 

-

3

7

,

 

4

5

5

.

5

,

 

9

6

 

}

,




{

 

-

5

4

,

 

-

1

2

0

,

 

4

5

5

.

5

,

 

2

6

 

}

,




}

;







l

o

c

a

l

 

e

v

e

n

t

 

=

 

1

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

s

 

=

 

{

 

0

,

 

0

,

 

0

,

 

0

,

 

0

 

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

(

)




l

o

c

a

l

 

l

o

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

 

i

 

=

 

1

,

 

#

s

p

a

w

n

s

 

d

o




i

f

 

(

 

s

p

a

w

n

s

[

i

]

 

=

=

 

0

 

o

r

 

n

o

t

 

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

(

s

p

a

w

n

s

[

i

]

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




l

o

c

 

=

 

S

P

A

W

N

_

L

O

C

S

[

i

]

;




s

p

a

w

n

s

[

i

]

 

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

 

e

q

.

C

h

o

o

s

e

R

a

n

d

o

m

(

2

0

7

0

2

3

,

 

2

0

7

2

8

4

,

 

2

0

7

0

2

4

,

 

2

0

7

2

9

1

)

,

 

0

,

 

0

,

 

l

o

c

[

1

]

,

 

l

o

c

[

2

]

,

 

l

o

c

[

3

]

,

 

l

o

c

[

4

]

 

)

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

s

p

a

w

n

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

 

i

 

=

 

1

,

 

#

s

p

a

w

n

s

 

d

o







i

f

 

(

 

s

p

a

w

n

s

[

i

]

 

~

=

 

0

 

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

I

D

(

)

 

=

=

 

s

p

a

w

n

s

[

i

]

 

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













s

p

a

w

n

s

[

i

]

 

=

 

0

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

S

O

R

R

O

W

S

O

N

G

_

S

P

A

W

N

I

D

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

v

e

n

t

 

=

 

1

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

H

P

_

E

V

E

N

T

S

[

e

v

e

n

t

]

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

 

 

S

a

r

y

r

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

u

p

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

b

o

u

n

d

s

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

b

o

u

n

d

s

*




D

e

s

p

a

w

n

(

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

b

o

u

n

d

s

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

 

5

7

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

S

a

r

y

r

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

s

i

g

n

a

l

(

S

O

R

R

O

W

S

O

N

G

_

T

Y

P

E

I

D

,

 

3

)

;

 




e

v

e

n

t

 

=

 

1

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

H

P

_

E

V

E

N

T

S

[

e

v

e

n

t

]

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







e

v

e

n

t

 

=

 

e

v

e

n

t

 

+

 

1

;




i

f

 

(

 

H

P

_

E

V

E

N

T

S

[

e

v

e

n

t

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

H

P

_

E

V

E

N

T

S

[

e

v

e

n

t

]

)

;










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

9

 

)

 

t

h

e

n




>

*

*

S

a

r

y

r

n

 

s

a

y

s

:

*

*

 

S

o

r

r

o

w

s

o

n

g

,

 

s

i

n

g

 

f

o

r

 

u

s

.

 

 

W

e

 

w

a

n

t

 

t

h

e

s

e

 

w

r

e

t

c

h

e

s

 

t

o

 

e

n

j

o

y

 

t

h

e

i

r

 

s

t

a

y

,

 

d

o

n

'

t

 

w

e

?




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

S

O

R

R

O

W

S

O

N

G

_

T

Y

P

E

I

D

,

 

1

)

;

 




S

p

a

w

n

(

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




>

*

*

S

a

r

y

r

n

 

s

a

y

s

:

*

*

 

T

h

i

s

 

f

i

l

t

h

 

i

s

 

p

r

o

v

i

n

g

 

t

o

 

b

e

 

a

 

c

h

a

l

l

e

n

g

e

!

 

 

S

o

r

r

o

w

s

o

n

g

,

 

a

t

t

a

c

k

 

t

h

e

s

e

 

m

o

r

t

a

l

s

!




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

S

O

R

R

O

W

S

O

N

G

_

T

Y

P

E

I

D

,

 

2

)

;

 




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

 

i

 

=

 

1

,

 

3

 

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

e

q

.

C

h

o

o

s

e

R

a

n

d

o

m

(

2

0

7

3

0

6

,

 

2

0

7

3

0

8

)

,

 

0

,

 

0

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

-

3

0

,

 

3

0

)

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

-

1

0

5

,

 

-

5

5

)

,

 

5

8

0

,

 

0

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

s

p

a

w

n

(

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

 


