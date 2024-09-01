# Defender Yoel

[Defender Yoel](/npc/150011) is a level 55 Half Elf Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).

## Dialog

**You say:** `hail`


>**Defender Yoel says:** Greetings, friend, and welcome to the Commons quarter of the Shadowhaven.









## Combat

if Defender Yoel enters combat  then

**Set a timer** named *combatsay* for 300 seconds

else

**Stop timer** named *combatsay*









## Timer(s)

>**Defender Yoel says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!







## On NPC Death

**Stop timer** named *combatsay*

