# A Stonefist Clansman

[A Stonefist Clansman](/npc/222009) is a level 66 Giant Warrior that spawns in [Plane of Earth](/zone/222).

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

7

;




l

o

c

a

l

 

B

I

R

A

K

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

5

;




l

o

c

a

l

 

B

I

R

A

K

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

3

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

2

,

 

3

6

9

4

4

3

,

 

3

6

9

4

4

4

,

 

3

6

9

4

4

5

 

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

B

I

R

A

K

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

 

S

t

o

n

e

f

i

s

t

 

C

l

a

n

s

m

a

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

0

9

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

B

I

R

A

K

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





