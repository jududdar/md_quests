# Rizlona

[Rizlona](/npc/212407) is a level 70 Dragon Warrior that spawns in [Tower of Solusek Ro](/zone/212).

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

3

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

7

1

7

,

 

*

*

x

:

*

*

 

-

9

8

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

a

 

w

a

r

d

e

r

 

o

f

 

R

i

z

l

o

n

a

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

0

2

2

,

 

*

*

x

:

*

*

 

-

1

0

8

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

 

R

i

z

l

o

n

a

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

0

2

2

,

 

*

*

x

:

*

*

 

-

1

1

1

8

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

 

R

i

z

l

o

n

a

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

9

7

5

,

 

*

*

x

:

*

*

 

-

1

1

0

2

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

Y

(

)

 

<

 

2

0

4

7

 

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

Y

(

)

 

>

 

2

5

3

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

-

1

1

0

3

,

 

2

3

8

4

,

 

-

9

0

5

,

 

1

2

8

)

;




e

.

s

e

l

f

:

S

e

t

G

u

a

r

d

S

p

o

t

(

-

1

1

0

3

,

 

2

3

8

4

,

 

-

9

0

5

,

 

1

2

8

)

;




*

*

R

i

z

l

o

n

a

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

R

i

z

l

o

n

a

 

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

R

i

z

l

o

n

a

 

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

 

 

R

i

z

l

o

n

a

 

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





