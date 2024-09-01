# Raex Pwodill

[Raex Pwodill](/npc/200258) is a level 70 Knight of Pestilence Warrior that spawns in [The Crypt of Decay](/zone/200).

Their primary faction is [KOS](/faction/5017).





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

 

9

9

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




*

*

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

p

 

=

 

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

 







i

f

 

(

 

h

p

 

a

n

d

 

h

p

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




h

p

:

S

e

t

B

o

d

y

T

y

p

e

(

3

,

 

f

a

l

s

e

)

;

 

 

 

 




h

p

:

S

e

t

S

p

e

c

i

a

l

A

b

i

l

i

t

y

(

2

4

,

 

0

)

;

 




h

p

:

S

e

t

S

p

e

c

i

a

l

A

b

i

l

i

t

y

(

3

5

,

 

0

)

;

 




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

d

e

p

o

p

"

,

 

1

1

7

0

0

0

0

0

,

 

h

p

)

;








