# Arlyxir

[Arlyxir](/npc/212023) is a level 75 Phoenix Warrior that spawns in [Tower of Solusek Ro](/zone/212).

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

 

1

8

9

1

,

 

*

*

x

:

*

*

 

1

6

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

 

A

r

l

y

x

i

r

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

6

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

1

6

5

,

 

*

*

x

:

*

*

 

1

7

2

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

 

A

r

l

y

x

i

r

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

6

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

2

0

7

,

 

*

*

x

:

*

*

 

1

7

1

3

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

 

A

r

l

y

x

i

r

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

6

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

2

0

7

,

 

*

*

x

:

*

*

 

1

7

3

8

)
















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

 

 

A

r

l

y

x

i

r

 

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

h

e

a

l

*

 

f

o

r

 

7

5

0

 

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

h

e

a

l

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

 

1

2

3

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

A

r

l

y

x

i

r

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

A

r

l

y

x

i

r

 

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

h

e

a

l

"

 

)

 

t

h

e

n




>

*

A

r

l

y

x

i

r

 

i

s

 

i

m

m

o

l

a

t

e

d

 

i

n

 

f

l

a

m

e

s

,

 

a

n

d

 

i

s

 

r

e

b

o

r

n

!

*




e

.

s

e

l

f

:

H

e

a

l

(

)

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

1

2

8

1

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

T

a

r

g

e

t

(

)

:

G

e

t

I

D

(

)

)

;

 





