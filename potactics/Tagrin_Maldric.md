# Tagrin Maldric

[Tagrin Maldric](/npc/214054) is a level 70 Troll Warrior that spawns in [Drunder, the Fortress of Zek](/zone/214).

Their primary faction is [The Diaku](/faction/1643).l

o

c

a

l

 

B

L

A

D

E

_

T

Y

P

E

1

 

=

 

2

1

4

3

1

0

;

 




l

o

c

a

l

 

B

L

A

D

E

_

T

Y

P

E

2

 

=

 

2

1

4

3

2

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

_

L

O

C

S

 

=

 

{




{

 

1

2

6

0

,

 

2

1

3

6

,

 

-

3

0

2

.

6

5

 

}

,




{

 

1

4

4

9

,

 

1

7

3

4

,

 

-

3

0

5

 

}

,




{

 

1

2

4

6

,

 

1

7

7

5

,

 

-

3

0

7

 

}

,




{

 

1

6

9

3

,

 

1

9

5

5

,

 

-

3

0

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

 

s

p

a

w

n

C

o

u

n

t

 

=

 

0

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

o

u

n

t

B

l

a

d

e

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

 

c

o

u

n

t

 

=

 

0

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

 

(

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

 

B

L

A

D

E

_

T

Y

P

E

1

 

o

r

 

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

 

B

L

A

D

E

_

T

Y

P

E

2

)

 

)

 

t

h

e

n




c

o

u

n

t

 

=

 

c

o

u

n

t

 

+

 

1

;













r

e

t

u

r

n

 

c

o

u

n

t

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

B

l

a

d

e

s

(

n

,

 

t

a

g

r

i

n

)




l

o

c

a

l

 

l

o

c

,

 

m

o

b

,

 

t

a

r

,

 

t

y

p

;




f

o

r

 

i

 

=

 

1

,

 

n

 

d

o




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

]

;







i

f

 

(

 

s

p

a

w

n

C

o

u

n

t

 

>

 

1

0

 

)

 

t

h

e

n

 




t

y

p

 

=

 

B

L

A

D

E

_

T

Y

P

E

2

;




e

l

s

e




t

y

p

 

=

 

B

L

A

D

E

_

T

Y

P

E

1

;










m

o

b

 

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

t

y

p

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

 

0

)

;




m

o

b

:

S

e

t

R

u

n

n

i

n

g

(

t

r

u

e

)

;




i

f

 

(

 

t

a

g

r

i

n

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




t

a

r

 

=

 

t

a

g

r

i

n

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

)

;







i

f

 

(

 

t

a

r

 

a

n

d

 

t

a

r

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




m

o

b

:

A

d

d

T

o

H

a

t

e

L

i

s

t

(

t

a

r

,

 

2

0

)

;










s

p

a

w

n

C

o

u

n

t

 

=

 

s

p

a

w

n

C

o

u

n

t

 

+

 

1

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

B

l

a

d

e

s

(

t

a

g

r

i

n

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

 

t

a

r

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

 

(

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

 

B

L

A

D

E

_

T

Y

P

E

1

 

o

r

 

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

 

B

L

A

D

E

_

T

Y

P

E

2

)

 

)

 

t

h

e

n







i

f

 

(

 

t

a

g

r

i

n

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




t

a

r

 

=

 

t

a

g

r

i

n

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

(

)

;







i

f

 

(

 

t

a

r

 

a

n

d

 

t

a

r

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

A

d

d

T

o

H

a

t

e

L

i

s

t

(

t

a

r

,

 

2

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

 

S

p

a

w

n




s

p

a

w

n

C

o

u

n

t

 

=

 

0

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

a

g

r

i

n

 

M

a

l

d

r

i

c

 

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

i

c

k

*

 

f

o

r

 

6

 

s

e

c

o

n

d

s




A

g

g

r

o

B

l

a

d

e

s

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

t

i

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

t

i

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

Y

(

)

 

<

 

1

6

8

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

T

a

g

r

i

n

 

M

a

l

d

r

i

c

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

T

a

g

r

i

n

 

M

a

l

d

r

i

c

 

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










l

o

c

a

l

 

b

l

a

d

e

s

 

=

 

C

o

u

n

t

B

l

a

d

e

s

(

)

;







i

f

 

(

 

b

l

a

d

e

s

 

<

 

3

 

)

 

t

h

e

n




S

p

a

w

n

B

l

a

d

e

s

(

3

 

-

 

b

l

a

d

e

s

,

 

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

i

f

 

(

 

b

l

a

d

e

s

 

<

 

5

 

)

 

t

h

e

n




S

p

a

w

n

B

l

a

d

e

s

(

1

,

 

e

.

s

e

l

f

)

;








