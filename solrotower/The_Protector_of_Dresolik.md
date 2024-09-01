# The Protector of Dresolik

[The Protector of Dresolik](/npc/212408) is a level 75 Giant Warrior that spawns in [Tower of Solusek Ro](/zone/212).

Their primary faction is [KOS](/faction/5017).





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

a

 

f

l

a

m

i

n

g

 

c

a

u

l

d

r

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

1

2

4

1

4

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

4

4

9

,

 

*

*

x

:

*

*

 

1

6

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

a

 

w

a

r

d

e

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

1

9

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

9

1

8

,

 

*

*

x

:

*

*

 

9

7

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

a

 

w

a

r

d

e

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

1

9

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

9

8

2

,

 

*

*

x

:

*

*

 

1

0

0

7

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

a

 

w

a

r

d

e

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

1

9

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

9

1

8

,

 

*

*

x

:

*

*

 

1

0

4

1

)
















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

 

3

6

0

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

d

e

p

o

p

"

 

)

 

t

h

e

n




*

*

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





