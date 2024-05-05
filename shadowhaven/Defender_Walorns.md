# Defender Walorns



[Defender Walorns](/npc/150039) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).



## Dialog

**You say:** `hail`



>**Defender Walorns says:** Hello, Soandso. If you are here to see the Trade Commissioner please sheath your weapons and proceed inside.
end



## Combat

if Defender Walorns enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Walorns says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*