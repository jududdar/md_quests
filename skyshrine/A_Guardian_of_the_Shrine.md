l

o

c

a

l

 

S

L

E

E

P

E

R

_

T

Y

P

E

 

=

 

1

2

8

0

9

4

;

 




l

o

c

a

l

 

S

H

O

U

T

_

T

Y

P

E

S

 

=

 

{

 

1

1

4

6

1

8

,

 

1

1

4

5

0

8

,

 

1

1

4

4

3

5

,

 

1

1

4

5

6

4

,

 

1

1

4

4

3

4

,

 

1

1

4

5

0

1

,

 

1

1

4

0

1

4

 

}

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

S

l

e

e

p

e

r

 

t

i

m

e

r

 

s

t

a

r

t

e

d

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

H

O

U

T

_

T

Y

P

E

S

)

 

d

o




n

p

c

 

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

B

y

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

i

d

)

;




i

f

 

(

 

n

p

c

 

a

n

d

 

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







i

f

 

(

 

i

 

=

=

 

1

 

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

n

p

c

,

 

t

r

u

e

,

 

1

5

0

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

C

l

e

a

n

N

a

m

e

(

)

.

.

"

 

s

h

o

u

t

s

,

 

'

B

E

W

A

R

E

!

 

 

T

h

e

 

S

l

e

e

p

e

r

 

h

a

s

 

b

e

e

n

 

a

w

a

k

e

n

e

d

!

 

 

F

l

e

e

 

t

h

e

 

s

h

r

i

n

e

 

i

m

m

e

d

i

a

t

e

l

y

,

 

i

t

 

i

n

t

e

n

d

s

 

d

e

a

t

h

 

t

o

 

a

l

l

 

h

e

r

e

!

'

"

)

;




e

l

s

e




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

n

p

c

,

 

t

r

u

e

,

 

6

0

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

C

l

e

a

n

N

a

m

e

(

)

.

.

"

 

s

h

o

u

t

s

,

 

'

B

E

W

A

R

E

!

 

 

B

E

W

A

R

E

!

 

 

T

h

e

 

S

l

e

e

p

e

r

 

h

a

s

 

b

e

e

n

 

a

w

a

k

e

n

e

d

!

 

 

H

e

 

m

e

a

n

s

 

d

e

a

t

h

 

f

o

r

 

a

l

l

 

w

h

o

 

r

e

m

a

i

n

 

h

e

r

e

!

 

 

T

i

m

e

 

i

s

 

s

h

o

r

t

,

 

f

l

e

e

 

t

h

e

 

S

k

y

s

h

r

i

n

e

 

n

o

w

 

i

f

 

y

o

u

 

v

a

l

u

e

 

y

o

u

r

 

l

i

f

e

!

'

"

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

l

e

e

p

e

r

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

l

e

e

p

e

r

"

 

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

r

e

p

o

p

*

 

f

o

r

 

8

6

4

0

0

 

s

e

c

o

n

d

s







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

S

L

E

E

P

E

R

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

3

2

8

,

 

4

4

7

,

 

4

6

,

 

0

,

 

"

K

e

r

a

f

y

r

m

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

P

r

i

m

a

r

y

F

a

c

t

i

o

n

(

)

 

=

=

 

4

3

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

S

e

t

N

P

C

A

g

g

r

o

(

t

r

u

e

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

S

p

a

w

n

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

 

s

p

a

w

n

 

i

n

 

s

p

a

w

n

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




s

p

a

w

n

:

D

i

s

a

b

l

e

(

f

a

l

s

e

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

p

o

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

 

s

p

a

w

n

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

S

p

a

w

n

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

 

s

p

a

w

n

 

i

n

 

s

p

a

w

n

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




s

p

a

w

n

:

E

n

a

b

l

e

(

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

z

o

n

e

 

s

p

a

w

n

s

 

e

n

a

b

l

e

d

"

)

;





