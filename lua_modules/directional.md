f

u

n

c

t

i

o

n

 

M

o

b

:

D

i

r

e

c

t

i

o

n

a

l

A

r

e

a

E

f

f

e

c

t

L

i

s

t

(

a

n

g

l

e

_

s

t

a

r

t

,

 

a

n

g

l

e

_

e

n

d

,

 

a

o

e

_

r

a

n

g

e

,

 

m

i

n

_

r

a

n

g

e

,

 

m

_

l

i

s

t

)







a

n

g

l

e

_

s

t

a

r

t

 

=

 

a

n

g

l

e

_

s

t

a

r

t

 

+

 

(

s

e

l

f

:

G

e

t

H

e

a

d

i

n

g

(

)

 

*

 

3

6

0

.

0

 

/

 

2

5

6

.

0

)

;




a

n

g

l

e

_

e

n

d

 

=

 

a

n

g

l

e

_

e

n

d

 

+

 

(

s

e

l

f

:

G

e

t

H

e

a

d

i

n

g

(

)

 

*

 

3

6

0

.

0

 

/

 

2

5

6

.

0

)

;







w

h

i

l

e

(

a

n

g

l

e

_

s

t

a

r

t

 

>

 

3

6

0

.

0

)

 

d

o




a

n

g

l

e

_

s

t

a

r

t

 

=

 

a

n

g

l

e

_

s

t

a

r

t

 

-

 

3

6

0

.

0

;










w

h

i

l

e

(

a

n

g

l

e

_

e

n

d

 

>

 

3

6

0

.

0

)

 

d

o




a

n

g

l

e

_

e

n

d

 

=

 

a

n

g

l

e

_

e

n

d

 

-

 

3

6

0

.

0

;










l

o

c

a

l

 

r

e

t

 

=

 

{

 

}

;




f

o

r

 

e

n

t

 

i

n

 

m

_

l

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

 

~

=

 

s

e

l

f

:

G

e

t

I

D

(

)

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

 

x

_

d

i

f

f

 

=

 

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

 

-

 

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

;




x

_

d

i

f

f

 

=

 

x

_

d

i

f

f

 

*

 

x

_

d

i

f

f

;







l

o

c

a

l

 

y

_

d

i

f

f

 

=

 

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

 

-

 

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

;




y

_

d

i

f

f

 

=

 

y

_

d

i

f

f

 

*

 

y

_

d

i

f

f

;







l

o

c

a

l

 

z

_

d

i

f

f

 

=

 

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

 

-

 

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

;




z

_

d

i

f

f

 

=

 

z

_

d

i

f

f

 

*

 

z

_

d

i

f

f

;







i

f

(

(

(

x

_

d

i

f

f

 

+

 

y

_

d

i

f

f

)

 

<

=

 

(

a

o

e

_

r

a

n

g

e

 

*

 

a

o

e

_

r

a

n

g

e

)

)

 

a

n

d

 

(

z

_

d

i

f

f

 

<

=

 

(

(

a

o

e

_

r

a

n

g

e

 

*

 

a

o

e

_

r

a

n

g

e

)

 

/

 

2

)

)

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

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

=

 

s

e

l

f

:

C

a

l

c

u

l

a

t

e

H

e

a

d

i

n

g

T

o

T

a

r

g

e

t

(

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

,

 

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

)

 

*

 

3

6

0

.

0

 

/

 

2

5

6

.

0

;




w

h

i

l

e

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

<

 

0

.

0

)

 

d

o




h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

=

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

+

 

3

6

0

.

0

;










w

h

i

l

e

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

>

 

3

6

0

.

0

)

 

d

o




h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

=

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

-

 

3

6

0

.

0

;










i

f

(

a

n

g

l

e

_

s

t

a

r

t

 

>

 

a

n

g

l

e

_

e

n

d

)

 

t

h

e

n




i

f

(

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

>

=

 

a

n

g

l

e

_

s

t

a

r

t

 

a

n

d

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

<

=

 

3

6

0

.

0

)

 

o

r

 

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

>

=

 

0

.

0

 

a

n

d

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

<

=

 

a

n

g

l

e

_

e

n

d

)

)

 

t

h

e

n




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

r

e

t

,

 

e

n

t

)

;







e

l

s

e




i

f

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

>

=

 

a

n

g

l

e

_

s

t

a

r

t

 

a

n

d

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

<

=

 

a

n

g

l

e

_

e

n

d

)

 

t

h

e

n




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

r

e

t

,

 

e

n

t

)

;






















r

e

t

u

r

n

 

r

e

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

 

N

P

C

:

D

i

r

e

c

t

i

o

n

a

l

A

r

e

a

E

f

f

e

c

t

L

i

s

t

(

a

n

g

l

e

_

s

t

a

r

t

,

 

a

n

g

l

e

_

e

n

d

,

 

a

o

e

_

r

a

n

g

e

,

 

m

i

n

_

r

a

n

g

e

,

 

m

_

l

i

s

t

)







a

n

g

l

e

_

s

t

a

r

t

 

=

 

a

n

g

l

e

_

s

t

a

r

t

 

+

 

(

s

e

l

f

:

G

e

t

H

e

a

d

i

n

g

(

)

 

*

 

3

6

0

.

0

 

/

 

2

5

6

.

0

)

;




a

n

g

l

e

_

e

n

d

 

=

 

a

n

g

l

e

_

e

n

d

 

+

 

(

s

e

l

f

:

G

e

t

H

e

a

d

i

n

g

(

)

 

*

 

3

6

0

.

0

 

/

 

2

5

6

.

0

)

;







w

h

i

l

e

(

a

n

g

l

e

_

s

t

a

r

t

 

>

 

3

6

0

.

0

)

 

d

o




a

n

g

l

e

_

s

t

a

r

t

 

=

 

a

n

g

l

e

_

s

t

a

r

t

 

-

 

3

6

0

.

0

;










w

h

i

l

e

(

a

n

g

l

e

_

e

n

d

 

>

 

3

6

0

.

0

)

 

d

o




a

n

g

l

e

_

e

n

d

 

=

 

a

n

g

l

e

_

e

n

d

 

-

 

3

6

0

.

0

;










l

o

c

a

l

 

r

e

t

 

=

 

{

 

}

;




f

o

r

 

e

n

t

 

i

n

 

m

_

l

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

 

~

=

 

s

e

l

f

:

G

e

t

I

D

(

)

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

 

x

_

d

i

f

f

 

=

 

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

 

-

 

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

;




x

_

d

i

f

f

 

=

 

x

_

d

i

f

f

 

*

 

x

_

d

i

f

f

;







l

o

c

a

l

 

y

_

d

i

f

f

 

=

 

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

 

-

 

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

;




y

_

d

i

f

f

 

=

 

y

_

d

i

f

f

 

*

 

y

_

d

i

f

f

;







l

o

c

a

l

 

z

_

d

i

f

f

 

=

 

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

 

-

 

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

;




z

_

d

i

f

f

 

=

 

z

_

d

i

f

f

 

*

 

z

_

d

i

f

f

;







i

f

(

(

(

x

_

d

i

f

f

 

+

 

y

_

d

i

f

f

)

 

<

=

 

(

a

o

e

_

r

a

n

g

e

 

*

 

a

o

e

_

r

a

n

g

e

)

)

 

a

n

d

 

(

z

_

d

i

f

f

 

<

=

 

(

(

a

o

e

_

r

a

n

g

e

 

*

 

a

o

e

_

r

a

n

g

e

)

 

/

 

2

)

)

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

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

=

 

s

e

l

f

:

C

a

l

c

u

l

a

t

e

H

e

a

d

i

n

g

T

o

T

a

r

g

e

t

(

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

,

 

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

)

 

*

 

3

6

0

.

0

 

/

 

2

5

6

.

0

;




w

h

i

l

e

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

<

 

0

.

0

)

 

d

o




h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

=

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

+

 

3

6

0

.

0

;










w

h

i

l

e

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

>

 

3

6

0

.

0

)

 

d

o




h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

=

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

-

 

3

6

0

.

0

;










i

f

(

a

n

g

l

e

_

s

t

a

r

t

 

>

 

a

n

g

l

e

_

e

n

d

)

 

t

h

e

n




i

f

(

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

>

=

 

a

n

g

l

e

_

s

t

a

r

t

 

a

n

d

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

<

=

 

3

6

0

.

0

)

 

o

r

 

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

>

=

 

0

.

0

 

a

n

d

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

<

=

 

a

n

g

l

e

_

e

n

d

)

)

 

t

h

e

n




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

r

e

t

,

 

e

n

t

)

;







e

l

s

e




i

f

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

>

=

 

a

n

g

l

e

_

s

t

a

r

t

 

a

n

d

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

<

=

 

a

n

g

l

e

_

e

n

d

)

 

t

h

e

n




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

r

e

t

,

 

e

n

t

)

;






















r

e

t

u

r

n

 

r

e

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

 

C

l

i

e

n

t

:

D

i

r

e

c

t

i

o

n

a

l

A

r

e

a

E

f

f

e

c

t

L

i

s

t

(

a

n

g

l

e

_

s

t

a

r

t

,

 

a

n

g

l

e

_

e

n

d

,

 

a

o

e

_

r

a

n

g

e

,

 

m

i

n

_

r

a

n

g

e

,

 

m

_

l

i

s

t

)







a

n

g

l

e

_

s

t

a

r

t

 

=

 

a

n

g

l

e

_

s

t

a

r

t

 

+

 

(

s

e

l

f

:

G

e

t

H

e

a

d

i

n

g

(

)

 

*

 

3

6

0

.

0

 

/

 

2

5

6

.

0

)

;




a

n

g

l

e

_

e

n

d

 

=

 

a

n

g

l

e

_

e

n

d

 

+

 

(

s

e

l

f

:

G

e

t

H

e

a

d

i

n

g

(

)

 

*

 

3

6

0

.

0

 

/

 

2

5

6

.

0

)

;







w

h

i

l

e

(

a

n

g

l

e

_

s

t

a

r

t

 

>

 

3

6

0

.

0

)

 

d

o




a

n

g

l

e

_

s

t

a

r

t

 

=

 

a

n

g

l

e

_

s

t

a

r

t

 

-

 

3

6

0

.

0

;










w

h

i

l

e

(

a

n

g

l

e

_

e

n

d

 

>

 

3

6

0

.

0

)

 

d

o




a

n

g

l

e

_

e

n

d

 

=

 

a

n

g

l

e

_

e

n

d

 

-

 

3

6

0

.

0

;










l

o

c

a

l

 

r

e

t

 

=

 

{

 

}

;




f

o

r

 

e

n

t

 

i

n

 

m

_

l

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

 

~

=

 

s

e

l

f

:

G

e

t

I

D

(

)

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

 

x

_

d

i

f

f

 

=

 

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

 

-

 

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

;




x

_

d

i

f

f

 

=

 

x

_

d

i

f

f

 

*

 

x

_

d

i

f

f

;







l

o

c

a

l

 

y

_

d

i

f

f

 

=

 

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

 

-

 

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

;




y

_

d

i

f

f

 

=

 

y

_

d

i

f

f

 

*

 

y

_

d

i

f

f

;







l

o

c

a

l

 

z

_

d

i

f

f

 

=

 

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

 

-

 

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

;




z

_

d

i

f

f

 

=

 

z

_

d

i

f

f

 

*

 

z

_

d

i

f

f

;







i

f

(

(

(

x

_

d

i

f

f

 

+

 

y

_

d

i

f

f

)

 

<

=

 

(

a

o

e

_

r

a

n

g

e

 

*

 

a

o

e

_

r

a

n

g

e

)

)

 

a

n

d

 

(

z

_

d

i

f

f

 

<

=

 

(

(

a

o

e

_

r

a

n

g

e

 

*

 

a

o

e

_

r

a

n

g

e

)

 

/

 

2

)

)

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

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

=

 

s

e

l

f

:

C

a

l

c

u

l

a

t

e

H

e

a

d

i

n

g

T

o

T

a

r

g

e

t

(

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

,

 

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

)

 

*

 

3

6

0

.

0

 

/

 

2

5

6

.

0

;




w

h

i

l

e

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

<

 

0

.

0

)

 

d

o




h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

=

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

+

 

3

6

0

.

0

;










w

h

i

l

e

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

>

 

3

6

0

.

0

)

 

d

o




h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

=

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

-

 

3

6

0

.

0

;










i

f

(

a

n

g

l

e

_

s

t

a

r

t

 

>

 

a

n

g

l

e

_

e

n

d

)

 

t

h

e

n




i

f

(

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

>

=

 

a

n

g

l

e

_

s

t

a

r

t

 

a

n

d

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

<

=

 

3

6

0

.

0

)

 

o

r

 

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

>

=

 

0

.

0

 

a

n

d

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

<

=

 

a

n

g

l

e

_

e

n

d

)

)

 

t

h

e

n




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

r

e

t

,

 

e

n

t

)

;







e

l

s

e




i

f

(

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

>

=

 

a

n

g

l

e

_

s

t

a

r

t

 

a

n

d

 

h

e

a

d

i

n

g

_

t

o

_

t

a

r

g

e

t

 

<

=

 

a

n

g

l

e

_

e

n

d

)

 

t

h

e

n




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

r

e

t

,

 

e

n

t

)

;






















r

e

t

u

r

n

 

r

e

t

;


