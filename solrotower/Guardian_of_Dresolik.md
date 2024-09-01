# Guardian of Dresolik

[Guardian of Dresolik](/npc/212046) is a level 68 Giant Warrior that spawns in [Tower of Solusek Ro](/zone/212).

Their primary faction is [KOS](/faction/5017).l

o

c

a

l

 

G

U

A

R

D

I

A

N

_

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

7

9

3

,

 

3

6

7

7

9

4

,

 

3

6

7

7

9

5

,

 

3

6

7

7

9

6

 

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

G

U

A

R

D

I

A

N

_

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

G

u

a

r

d

i

a

n

 

o

f

 

D

r

e

s

o

l

i

k

]

(

/

n

p

c

/

2

1

2

0

4

6

)

 

)

 

t

h

e

n

 




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

T

h

e

 

P

r

o

t

e

c

t

o

r

 

o

f

 

D

r

e

s

o

l

i

k

]

(

/

n

p

c

/

2

1

2

4

0

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

 

1

5

8

4

,

 

*

*

x

:

*

*

 

6

0

6

)



















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

 

>

 

9

7

8

 

o

r

 

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

 

5

5

8

 

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

G

u

a

r

d

i

a

n

 

o

f

 

D

r

e

s

o

l

i

k

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

G

u

a

r

d

i

a

n

 

o

f

 

D

r

e

s

o

l

i

k

 

c

a

s

t

s

:

*

*

 

[

A

n

n

u

l

 

S

e

l

f

]

(

/

s

p

e

l

l

/

2

8

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

 

 

G

u

a

r

d

i

a

n

 

o

f

 

D

r

e

s

o

l

i

k

 

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

 

6

 

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





