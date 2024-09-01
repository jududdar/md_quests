l

o

c

a

l

 

B

A

D

_

C

O

O

R

D

S

 

=

 

{







{

 

-

1

0

0

0

,

 

6

7

0

,

	

	




-

1

0

0

0

,

 

1

0

0

0

,

	

	




2

5

4

,

 

1

0

0

0

,

	

	




}

,







{

 

-

1

6

6

,

 

9

0

0

,

	

	




-

6

4

0

,

 

6

4

0

,

	

	




-

2

0

0

,

 

-

1

,

	

	

	




}

,







{

 

3

7

5

,

 

7

5

0

,

	

	




5

0

0

,

 

6

4

0

,

	

	




-

1

0

0

0

,

 

1

0

0

0

,

	

	




}

,







{

 

3

6

5

,

 

7

5

0

,

	

	




-

6

4

0

,

 

-

5

0

0

,

	

	




-

1

0

0

0

,

 

1

0

0

0

,

	

	




}

,




}

;







l

o

c

a

l

 

c

h

e

a

t

e

r

s

 

=

 

{

}

;




l

o

c

a

l

 

c

h

e

a

t

e

r

s

T

o

S

l

a

y

 

=

 

f

a

l

s

e

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

 

1

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

 

S

i

g

n

a

l

s




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

h

e

a

t

e

r

s

,

 

e

.

s

i

g

n

a

l

)

;




i

f

 

(

 

n

o

t

 

c

h

e

a

t

e

r

s

T

o

S

l

a

y

 

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

k

i

l

l

_

l

i

s

t

*

 

f

o

r

 

0

 

s

e

c

o

n

d

s







c

h

e

a

t

e

r

s

T

o

S

l

a

y

 

=

 

t

r

u

e

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

t

o

s

t

r

i

n

g

(

e

.

s

i

g

n

a

l

)

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

k

i

l

l

_

l

i

s

t

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

 

i

 

=

 

#

c

h

e

a

t

e

r

s

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

;




i

f

 

(

 

i

 

>

 

0

 

)

 

t

h

e

n




c

l

i

e

n

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

C

l

i

e

n

t

B

y

I

D

(

c

h

e

a

t

e

r

s

[

i

]

)

;




i

f

 

(

 

c

l

i

e

n

t

 

a

n

d

 

c

l

i

e

n

t

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

 

c

l

i

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

 

>

 

1

3

6

6

 

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

X

(

)

 

<

 

1

0

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

1

0

9

2

,

 

0

,

 

2

3

5

,

 

6

4

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

.

s

e

l

f

:

C

a

s

t

S

p

e

l

l

(

9

8

2

,

 

c

l

i

e

n

t

:

G

e

t

I

D

(

)

,

 

0

,

 

1

0

0

)

;

 







t

a

b

l

e

.

r

e

m

o

v

e

(

c

h

e

a

t

e

r

s

,

 

i

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

 

c

l

i

e

n

t

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

C

l

i

e

n

t

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

 

c

l

i

e

n

t

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

 

c

l

i

e

n

t

 

i

n

 

c

l

i

e

n

t

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

o

t

 

c

l

i

e

n

t

:

G

e

t

G

M

(

)

 

)

 

t

h

e

n




f

o

r

 

_

,

 

c

o

o

r

d

s

 

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

A

D

_

C

O

O

R

D

S

)

 

d

o







i

f

 

(

 

c

l

i

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

 

>

 

c

o

o

r

d

s

[

1

]

 

a

n

d

 

c

l

i

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

 

<

 

c

o

o

r

d

s

[

2

]




a

n

d

 

c

l

i

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

 

>

 

c

o

o

r

d

s

[

3

]

 

a

n

d

 

c

l

i

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

 

<

 

c

o

o

r

d

s

[

4

]




a

n

d

 

c

l

i

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

 

>

 

c

o

o

r

d

s

[

5

]

 

a

n

d

 

c

l

i

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

 

<

 

c

o

o

r

d

s

[

6

]




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

C

a

s

t

S

p

e

l

l

(

9

8

2

,

 

c

l

i

e

n

t

:

G

e

t

I

D

(

)

,

 

0

,

 

1

0

0

)

;

 




r

e

t

u

r

n

;






















i

f

 

(

 

c

h

e

a

t

e

r

s

T

o

S

l

a

y

 

a

n

d

 

#

c

h

e

a

t

e

r

s

 

=

=

 

0

 

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

k

i

l

l

_

l

i

s

t

*




c

h

e

a

t

e

r

s

T

o

S

l

a

y

 

=

 

f

a

l

s

e

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

X

(

)

 

>

 

5

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

5

0

0

,

 

0

,

 

2

5

5

,

 

0

)

;











