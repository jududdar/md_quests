# Aramin the Spider Guardian

[Aramin the Spider Guardian](/npc/205095) is a level 68 Arachnid Warrior that spawns in [Plane of Disease](/zone/205).

Their primary faction is [Inhabitants of Disease](/faction/1654).l

o

c

a

l

 

M

A

L

E

V

E

L

E

R

_

T

Y

P

E

 

=

 

2

0

5

1

5

7

;

 




l

o

c

a

l

 

S

E

R

I

O

U

N

_

T

Y

P

E

 

=

 

2

0

5

1

5

8

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




1

7

6

3

,

 

2

5

9

,

	




1

7

8

9

,

 

2

2

6

,




1

8

4

2

,

 

1

9

9

,




1

7

5

0

,

 

2

1

4

,




1

7

2

1

,

 

2

4

7

,

	




1

7

4

6

,

 

1

8

7

,




1

7

8

3

,

 

1

7

7

,




1

8

8

9

,

 

2

7

0

,




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







l

o

c

a

l

 

x

,

 

y

,

 

t

;




l

o

c

a

l

 

z

 

=

 

3

7

3

;




l

o

c

a

l

 

r

1

 

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

 

2

)

;




l

o

c

a

l

 

r

2

 

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

7

,

 

8

)

;




i

f

 

(

 

r

1

 

=

=

 

2

 

)

 

t

h

e

n




r

2

 

=

 

8

;
















f

o

r

 

i

 

=

 

r

1

,

 

r

2

 

d

o







i

f

 

(

 

i

 

<

 

5

 

)

 

t

h

e

n




t

 

=

 

S

E

R

I

O

U

N

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




t

 

=

 

M

A

L

E

V

E

L

E

R

_

T

Y

P

E

;










x

 

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

*

2

-

1

]

;




y

 

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

*

2

]

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

t

,

 

0

,

 

0

,

 

x

,

 

y

,

 

z

,

 

0

)

;





