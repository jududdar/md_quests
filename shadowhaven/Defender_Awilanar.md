# Defender Awilanar



[Defender Awilanar](/npc/150288) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).



## Dialog

**You say:** `hail`



>**Defender Awilanar says:** Hello there, I am Awilanar, one of the finest front line archers ever to sling an arrow.  Shadowhaven may rest easy on my watch- given a fair shot, I could hit a rabbit at night in deep fog, let there be no doubt.
end



## Combat

if Defender Awilanar enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Awilanar says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*