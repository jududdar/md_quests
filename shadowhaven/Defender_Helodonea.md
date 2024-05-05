# Defender Helodonea



[Defender Helodonea](/npc/150300) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).



## Dialog

**You say:** `hail`



>**Defender Helodonea says:** Welcome to House Fordel, Soandso.  It's great to meet you.
end



## Combat

if Defender Helodonea enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Helodonea says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*