# Defender Teerlals

[Defender Teerlals](/npc/150301) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).

## Dialog

**You say:** `hail`


>**Defender Teerlals says:** Hail, Soandso. If you are here to register for trading in the Haven please step inside and speak with the Trade Commissioner for further details.









## Combat

if Defender Teerlals enters combat  then

**Set a timer** named *combatsay* for 300 seconds

else

**Stop timer** named *combatsay*









## Timer(s)

>**Defender Teerlals says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!







## On NPC Death

**Stop timer** named *combatsay*

