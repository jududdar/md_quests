# Defender Dribsla

[Defender Dribsla](/npc/150037) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).

## Dialog

**You say:** `hail`


>**Defender Dribsla says:** Hi there. I'm a new recruit, so I sure hope I don't let Garon down. Trust me, you don't want to see him when he is angry.









## Combat

if Defender Dribsla enters combat  then

**Set a timer** named *combatsay* for 300 seconds

else

**Stop timer** named *combatsay*









## Timer(s)

>**Defender Dribsla says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!







## On NPC Death

**Stop timer** named *combatsay*

