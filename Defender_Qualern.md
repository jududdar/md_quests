# Defender Qualern

[Defender Qualern](/npc/150293) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).

## Dialog

**You say:** `hail`


>**Defender Qualern says:** Hello, Soandso. Inside is our main training facilities of new defender recruits. If you wish to go inside please keep to yourself as there may be some training exercises going on.









## Combat

if Defender Qualern enters combat  then

**Set a timer** named *combatsay* for 300 seconds

else

**Stop timer** named *combatsay*









## Timer(s)

>**Defender Qualern says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!







## On NPC Death

**Stop timer** named *combatsay*

