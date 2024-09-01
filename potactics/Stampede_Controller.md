l

o

c

a

l

 

B

O

A

R

1

_

T

Y

P

E

 

=

 

2

1

4

3

0

1

;

 




l

o

c

a

l

 

B

O

A

R

2

_

T

Y

P

E

 

=

 

2

1

4

3

0

2

;

 




l

o

c

a

l

 

P

I

G

L

E

T

_

T

Y

P

E

 

=

 

2

1

4

3

0

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

_

L

O

C

S

_

X

 

=

 

{

 

1

2

0

5

,

 

1

2

0

0

,

 

1

2

1

0

,

 

1

2

0

0

,

 

1

2

0

5

,

 

1

2

0

0

,

 

1

2

1

0

,

 

1

2

0

0

,

 

1

2

1

0

,

 

1

2

0

5

 

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

_

Y

 

=

 

{

 

-

3

0

0

,

 

-

3

0

0

,

 

-

3

1

0

,

 

-

3

2

0

,

 

-

3

1

0

,

 

-

3

1

0

,

 

-

3

1

5

,

 

-

3

1

5

,

 

-

3

0

0

,

 

-

3

1

5

 

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

B

o

a

r

s

(

)




l

o

c

a

l

 

y

,

 

n

p

c

,

 

p

a

u

s

e

;




l

o

c

a

l

 

z

 

=

 

-

2

8

6

.

6

2

5

;




l

o

c

a

l

 

x

2

,

 

x

3

,

 

y

2

,

 

y

3

;










f

o

r

 

j

 

=

 

1

,

 

4

 

d

o




p

a

u

s

e

 

=

 

1

0

 

+

 

j

 

*

 

4

;







f

o

r

 

i

,

 

x

 

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

_

L

O

C

S

_

X

)

 

d

o







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

_

Y

[

i

]

;







i

f

 

(

 

j

 

=

=

 

4

 

a

n

d

 

i

 

>

 

1

 

)

 

t

h

e

n




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

 

i

 

=

=

 

1

 

o

r

 

i

 

=

=

 

4

 

o

r

 

i

 

=

=

 

7

 

)

 

t

h

e

n




x

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

4

8

5

,

7

5

0

)

;




y

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

-

3

3

0

,

 

3

0

0

)

;







i

f

 

(

 

i

 

=

=

 

1

 

a

n

d

 

j

 

=

=

 

1

 

)

 

t

h

e

n




x

3

 

=

 

x

2

;

	




y

3

 

=

 

y

2

;







e

l

s

e

i

f

 

(

 

i

 

=

=

 

1

0

 

)

 

t

h

e

n




x

2

 

=

 

9

2

5

;




y

2

 

=

 

2

2

0

;










i

f

 

(

 

j

 

=

=

 

4

 

)

 

t

h

e

n




z

 

=

 

-

2

9

4

.

7

5

;




p

a

u

s

e

 

=

 

1

4

;




n

p

c

 

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

P

I

G

L

E

T

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

 

x

,

 

y

,

 

z

,

 

0

)

;




x

2

 

=

 

x

3

;




y

2

 

=

 

y

3

;




e

l

s

e




z

 

=

 

-

2

8

6

.

6

2

5

;




n

p

c

 

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

B

O

A

R

1

_

T

Y

P

E

,

 

B

O

A

R

2

_

T

Y

P

E

)

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







n

p

c

 

=

 

n

p

c

:

C

a

s

t

T

o

N

P

C

(

)

;




n

p

c

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




n

p

c

:

S

e

t

W

a

n

d

e

r

T

y

p

e

(

6

)

;




n

p

c

:

S

e

t

P

a

u

s

e

T

y

p

e

(

1

)

;




n

p

c

:

A

d

d

W

a

y

p

o

i

n

t

(

x

,

 

y

,

 

z

,

 

-

1

,

 

p

a

u

s

e

,

 

f

a

l

s

e

)

;




n

p

c

:

A

d

d

W

a

y

p

o

i

n

t

(

1

1

4

0

,

 

-

2

4

0

,

 

z

,

 

-

1

,

 

0

,

 

f

a

l

s

e

)

;




n

p

c

:

A

d

d

W

a

y

p

o

i

n

t

(

9

2

5

,

 

-

2

4

0

,

 

z

,

 

-

1

,

 

0

,

 

f

a

l

s

e

)

;




n

p

c

:

A

d

d

W

a

y

p

o

i

n

t

(

x

2

,

 

y

2

,

 

z

,

 

-

1

,

 

0

,

 

f

a

l

s

e

)

;




n

p

c

:

A

d

d

W

a

y

p

o

i

n

t

(

9

2

5

,

 

2

2

0

,

 

z

,

 

-

1

,

 

0

,

 

f

a

l

s

e

)

;




n

p

c

:

A

d

d

W

a

y

p

o

i

n

t

(

1

2

0

0

,

 

2

2

0

,

 

z

,

 

-

1

,

 

0

,

 

f

a

l

s

e

)

;




n

p

c

:

A

d

d

W

a

y

p

o

i

n

t

(

1

2

0

0

,

 

-

3

2

0

,

 

z

,

 

-

1

,

 

0

,

 

f

a

l

s

e

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

t

i

m

e

r

(

"

s

t

a

m

p

"

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

4

0

,

 

1

2

0

)

 

*

 

6

0

0

0

0

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

s

t

a

m

p

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

e

t

_

t

i

m

e

r

(

"

s

t

a

m

p

"

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

4

0

,

 

1

2

0

)

 

*

 

6

0

0

0

0

)

;







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

R

a

l

l

o

s

 

Z

e

k

 

t

h

e

 

W

a

r

l

o

r

d

]

(

/

n

p

c

/

2

1

4

3

1

2

)

 

)

 

t

h

e

n

 




*

*

Z

o

n

e

 

W

i

d

e

 

E

m

o

t

e

:

*

*

 

<

s

p

a

n

 

c

l

a

s

s

=

"

t

e

x

t

-

w

a

r

n

i

n

g

"

>

*

Y

o

u

 

h

e

a

r

 

t

h

e

 

p

o

u

n

d

i

n

g

 

o

f

 

h

o

o

v

e

s

.

*

<

/

s

p

a

n

>




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

p

a

w

n

*

 

f

o

r

 

1

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

p

a

w

n

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




S

p

a

w

n

B

o

a

r

s

(

)

;





