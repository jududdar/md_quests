# Defender Gerlinson

[Defender Gerlinson](/npc/150035) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).

## Dialog

**You say:** `hail`


>**Defender Gerlinson says:** Hello, Soandso, and welcome to Shadowhaven.  There is much that lies inside to be seen so I will not keep you waiting. Good luck to you.









## Combat

if Defender Gerlinson enters combat  then

**Set a timer** named *combatsay* for 300 seconds

else

**Stop timer** named *combatsay*









## Timer(s)

>**Defender Gerlinson says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!







## On NPC Death

**Stop timer** named *combatsay*

