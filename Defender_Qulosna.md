# Defender Qulosna

[Defender Qulosna](/npc/150060) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).

## Dialog

**You say:** `hail`


>**Defender Qulosna says:** Fine day in the Haven, is it not Soandso? I think this might be a nice time for a break at the tavern, if I don't say so myself.









## Combat

if Defender Qulosna enters combat  then

**Set a timer** named *combatsay* for 300 seconds

else

**Stop timer** named *combatsay*









## Timer(s)

>**Defender Qulosna says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!







## On NPC Death

**Stop timer** named *combatsay*

