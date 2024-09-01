





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

3

4

7

0

0

,

 

3

3

4

7

0

1

,

 

3

3

4

7

3

2

 

}

;




l

o

c

a

l

 

I

N

V

I

S

_

I

A

N

I

T

O

R

 

=

 

1

6

3

0

8

6

;







f

u

n

c

t

i

o

n

 

C

h

e

c

k

S

p

a

w

n

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

 

I

N

V

I

S

_

I

A

N

I

T

O

R

 

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













i

f

 

(

 

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

=

 

3

 

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

#

P

r

a

s

t

_

I

a

n

i

t

o

r

 

d

i

d

 

n

o

t

 

s

p

a

w

n

;

 

r

e

p

o

p

p

i

n

g

"

)

;




D

e

p

o

p

S

p

a

w

n

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

r

e

p

o

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

S

p

a

w

n

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

 

I

N

V

I

S

_

I

A

N

I

T

O

R

 

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

t

r

u

e

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




C

h

e

c

k

S

p

a

w

n

s

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

r

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

p

o

p

*




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

s

p

a

w

n

_

f

r

o

m

_

s

p

a

w

n

2

(

i

d

)

;








