# Lord Mithaniel Marr

[Lord Mithaniel Marr](/npc/220020) is a level 77 Mithaniel Marr Paladin that spawns in [Temple of Marr](/zone/220).

Their primary faction is [Battalion of Marr](/faction/1656).l

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

0

0

2

5

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

7

2

2

7

,

 

3

6

6

6

0

4

,

 

3

6

7

1

6

3

 

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

 

2

 

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

1

,

 

f

a

l

s

e

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

 

1

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

 

1

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

 

 

L

o

r

d

 

M

i

t

h

a

n

i

e

l

 

M

a

r

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

X

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




*

*

L

o

r

d

 

M

i

t

h

a

n

i

e

l

 

M

a

r

r

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

L

o

r

d

 

M

i

t

h

a

n

i

e

l

 

M

a

r

r

 

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

 

n

p

c

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

 

0

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

o

t

 

n

p

c

 

o

r

 

n

o

t

 

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




k

i

l

l

e

d

 

=

 

k

i

l

l

e

d

 

+

 

1

;













i

f

 

(

 

k

i

l

l

e

d

 

=

=

 

3

 

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

 








