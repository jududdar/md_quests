# Defender Jerlen

[Defender Jerlen](/npc/150189) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).



## Dialog

**You say:** `hail`


>**Defender Jerlen says:** Doing my rounds can't ya see? Catch me later at the Knights Inn if you got something important to discuss.









## Combat

if Defender Jerlen enters combat  then

**Set a timer** named *combatsay* for 300 seconds

else

**Stop timer** named *combatsay*









## Timer(s)

>**Defender Jerlen says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!







## On NPC Death

**Stop timer** named *combatsay*

