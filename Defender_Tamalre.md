# Defender Tamalre

[Defender Tamalre](/npc/150289) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).

## Dialog

**You say:** `hail`


>**Defender Tamalre says:** Hello, Soandso, I am an archer of the Fordel. I represent the first line of defense shall the Haven ever be invaded.









## Combat

if Defender Tamalre enters combat  then

**Set a timer** named *combatsay* for 300 seconds

else

**Stop timer** named *combatsay*









## Timer(s)

>**Defender Tamalre says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!







## On NPC Death

**Stop timer** named *combatsay*

