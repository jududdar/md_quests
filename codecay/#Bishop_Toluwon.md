# Bishop Toluwon

[Bishop Toluwon](/npc/200228) is a level 70 Lepertoloth Cleric that spawns in [The Crypt of Decay](/zone/200).

Their primary faction is [KOS](/faction/5017).l

o

c

a

l

 

K

N

I

G

H

T

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

2

2

5

;




l

o

c

a

l

 

M

A

G

U

S

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

2

2

6

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

d

e

p

o

p

*

 

f

o

r

 

1

1

7

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

B

y

I

D

(

K

N

I

G

H

T

_

S

P

A

W

N

I

D

)

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

B

y

I

D

(

M

A

G

U

S

_

S

P

A

W

N

I

D

)

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




*

*

B

i

s

h

o

p

 

T

o

l

u

w

o

n

 

d

e

s

p

a

w

n

s

.

*

*
















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

 

 

B

i

s

h

o

p

 

T

o

l

u

w

o

n

 

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




e

q

.

p

a

u

s

e

_

t

i

m

e

r

(

"

d

e

p

o

p

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

r

e

s

u

m

e

_

t

i

m

e

r

(

"

d

e

p

o

p

"

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

A

 

r

a

s

p

y

 

v

o

i

c

e

 

i

s

 

h

e

a

r

d

 

a

s

 

t

h

e

 

H

i

g

h

 

P

r

i

e

s

t

 

b

e

g

i

n

s

 

t

o

 

s

p

e

a

k

,

 

'

Y

o

u

 

h

a

v

e

 

c

o

m

e

 

f

a

r

 

t

o

 

s

e

e

k

 

y

o

u

r

 

d

e

m

i

s

e

.

 

R

a

e

x

!

 

V

i

n

d

o

r

!

 

M

y

 

g

e

n

e

r

a

l

s

 

t

o

 

m

e

.

 

S

l

a

y

 

t

h

e

s

e

 

i

n

f

i

d

e

l

s

 

i

n

 

t

h

e

 

n

a

m

e

 

o

f

 

o

u

r

 

l

o

r

d

 

t

h

e

 

P

l

a

g

u

e

b

r

i

n

g

e

r

.

'

*

<

/

s

p

a

n

>







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

B

y

I

D

(

K

N

I

G

H

T

_

S

P

A

W

N

I

D

)

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

B

y

I

D

(

M

A

G

U

S

_

S

P

A

W

N

I

D

)

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







*

*

S

p

a

w

n

 

N

P

C

:

*

*

 

 

[

\

#

H

i

g

h

 

P

r

i

e

s

t

 

U

l

t

o

r

 

S

z

a

n

v

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

0

0

2

4

5

)

 

a

t

 

(

*

*

y

:

*

*

 

3

1

8

,

 

*

*

x

:

*

*

 

3

0

6

)




*

*

S

p

a

w

n

 

N

P

C

:

*

*

 

 

[

\

#

V

i

n

d

o

r

 

M

a

w

n

i

l

]

(

/

n

p

c

/

2

0

0

2

6

1

)

 

a

t

 

(

*

*

y

:

*

*

 

2

9

4

,

 

*

*

x

:

*

*

 

2

0

0

)




*

*

S

p

a

w

n

 

N

P

C

:

*

*

 

 

[

\

#

R

a

e

x

 

P

w

o

d

i

l

l

]

(

/

n

p

c

/

2

0

0

2

5

8

)

 

a

t

 

(

*

*

y

:

*

*

 

2

4

1

,

 

*

*

x

:

*

*

 

4

9

6

)


