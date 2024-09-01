# A Rock Studded Champion

[A Rock Studded Champion](/npc/222010) is a level 66 Giant Warrior that spawns in [Plane of Earth](/zone/222).

Their primary faction is [KOS](/faction/5017).l

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

M

A

N

_

I

D

 

=

 

3

6

9

4

8

8

;




l

o

c

a

l

 

G

A

L

R

O

N

A

R

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

6

;




l

o

c

a

l

 

G

A

L

R

O

N

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

 

=

 

3

6

9

4

9

4

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

4

4

6

,

 

3

6

9

4

4

7

,

 

3

6

9

4

4

8

,

 

3

6

9

4

4

9

 

}

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

0

0

0

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

w

i

t

h

_

t

i

m

e

r

(

G

A

L

R

O

N

A

R

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

I

N

V

I

S

_

M

A

N

_

I

D

,

 

1

0

0

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







i

f

 

(

 

n

o

t

 

*

*

s

p

a

w

n

e

d

 

N

P

C

:

*

*

 

 

[

A

 

R

o

c

k

 

S

t

u

d

d

e

d

 

C

h

a

m

p

i

o

n

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

1

0

)

 

)

 

t

h

e

n

 







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

G

A

L

R

O

N

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

,

 

1

0

0

0

)

;







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

S

P

A

W

N

I

D

S

[

1

]

,

 

t

*

1

0

0

0

)

;





