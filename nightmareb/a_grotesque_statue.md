# a grotesque statue

[a grotesque statue](/npc/221043) is a level 63 Nightmare Gargoyle Warrior that spawns in [The Lair of Terris Thule](/zone/221).

Their primary faction is [KOS](/faction/5017).l

o

c

a

l

 

e

n

t

i

t

y

I

D

s

 

=

 

{

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

 

6

0

 

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

l

a

y

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

a

t

t

a

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







e

n

t

i

t

y

I

D

s

[

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

I

D

(

)

]

 

=

 

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

 

 

a

 

g

r

o

t

e

s

q

u

e

 

s

t

a

t

u

e

 

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




l

o

c

a

l

 

i

d

 

=

 

e

n

t

i

t

y

I

D

s

[

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

I

D

(

)

]

;




i

f

 

(

 

i

d

 

a

n

d

 

i

d

 

=

=

 

-

1

9

5

4

 

)

 

t

h

e

n




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

3

6

5

3

9

7

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




e

l

s

e

i

f

 

(

 

i

d

 

a

n

d

 

i

d

 

=

=

 

-

1

7

4

8

 

)

 

t

h

e

n




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

3

6

6

0

5

3

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




e

l

s

e

i

f

 

(

 

i

d

 

a

n

d

 

i

d

 

=

=

 

-

1

7

3

6

 

)

 

t

h

e

n




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

3

6

6

1

7

6

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




e

l

s

e

i

f

 

(

 

i

d

 

a

n

d

 

i

d

 

=

=

 

-

1

9

5

8

 

)

 

t

h

e

n




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

3

6

7

2

3

2

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







e

n

t

i

t

y

I

D

s

[

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

I

D

(

)

]

 

=

 

n

i

l

;




*

*

a

 

g

r

o

t

e

s

q

u

e

 

s

t

a

t

u

e

 

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

l

a

y

"

 

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

l

a

y

*




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

A

p

p

e

a

r

a

n

c

e

(

3

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

a

t

t

a

c

k

"

 

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

a

t

t

a

c

k

*




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

A

g

g

r

o

R

a

n

g

e

(

5

0

0

)

;





