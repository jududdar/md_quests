# Aerin`Dar

[Aerin`Dar](/npc/208074) is a level 70 Dragon Warrior that spawns in [Plane of Valor](/zone/208).

Their primary faction is [Beta KOS](/faction/479).l

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

8

2

0

7

;




l

o

c

a

l

 

M

I

N

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

8

1

7

5

;

 




l

o

c

a

l

 

R

A

H

L

G

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

8

1

7

6

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

4

7

2

2

0

,

 

3

4

7

2

2

1

,




3

4

7

2

1

9

,

 

3

4

7

2

1

7

,




3

4

7

2

1

6

,

 

3

4

7

2

1

5

,




3

4

7

2

1

8

,

 

3

4

7

2

1

4

,

 

3

4

7

2

1

3




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

 

W

a

k

e

U

p

(

.

.

.

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




l

o

c

a

l

 

i

 

=

 

1

;




l

o

c

a

l

 

i

d

x

 

=

 

s

e

l

e

c

t

(

i

,

 

.

.

.

)

;




w

h

i

l

e

 

(

i

d

x

)

 

d

o




i

f

 

(

 

S

P

A

W

N

I

D

S

[

i

d

x

]

 

)

 

t

h

e

n




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

S

P

A

W

N

I

D

S

[

i

d

x

]

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




n

p

c

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

2

4

,

 

0

)

;

 




n

p

c

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

3

5

,

 

0

)

;

 




n

p

c

:

S

e

t

B

o

d

y

T

y

p

e

(

1

,

 

f

a

l

s

e

)

;

	










i

 

=

 

i

 

+

 

1

;




i

d

x

 

=

 

s

e

l

e

c

t

(

i

,

 

.

.

.

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

 

R

e

s

p

a

w

n

A

d

d

s

(

)




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

 

3

6

0

,

 

2

5

2

8

,

 

3

9

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

8

5

)

;




R

e

s

p

a

w

n

A

d

d

s

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

 

8

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

6

5

)

;




W

a

k

e

U

p

(

1

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

4

5

)

;




W

a

k

e

U

p

(

3

,

 

4

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

 

4

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

2

5

)

;




W

a

k

e

U

p

(

5

,

 

6

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




W

a

k

e

U

p

(

7

,

 

8

,

 

9

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

R

a

t

i

o

(

)

 

<

 

8

6

 

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

 

3

 

s

e

c

o

n

d

s







i

f

 

 

A

e

r

i

n

-

D

a

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

Z

(

)

 

>

 

1

2

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

 

2

1

0

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

8

8

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

8

5

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

M

I

N

I

O

N

_

T

Y

P

E

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

R

A

H

L

G

O

N

_

T

Y

P

E

)

;




R

e

s

p

a

w

n

A

d

d

s

(

)

;








