# Defender Kealren



[Defender Kealren](/npc/150004) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).



## Dialog

**You say:** `hail`



>**Defender Kealren says:** Hi there stranger, it's nice to see a new face in the Haven.  I'm currently on patrol, so please catch me another time.
end



## Combat

if Defender Kealren enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Kealren says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*