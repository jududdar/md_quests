# Defender Feorlso

[Defender Feorlso](/npc/150298) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).

## Dialog

**You say:** `hail`


>**Defender Feorlso says:** Greetings to you. If you are hear to conduct official business with the banker, please be patient as they are busy with the many merchants that visit them each day.









## Combat

if Defender Feorlso enters combat  then

**Set a timer** named *combatsay* for 300 seconds

else

**Stop timer** named *combatsay*









## Timer(s)

>**Defender Feorlso says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!







## On NPC Death

**Stop timer** named *combatsay*

