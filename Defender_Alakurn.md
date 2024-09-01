# Defender Alakurn

[Defender Alakurn](/npc/150031) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).

## Dialog

**You say:** `hail`


>**Defender Alakurn says:** Hail, Soandso. Are you leaving the Haven?  If so, be sure to visit soon and see how our city continues to prosper more and more with the passing days.









## Combat

if Defender Alakurn enters combat  then

**Set a timer** named *combatsay* for 300 seconds

else

**Stop timer** named *combatsay*









## Timer(s)

>**Defender Alakurn says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!







## On NPC Death

**Stop timer** named *combatsay*

