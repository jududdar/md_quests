# Defender Erotans



[Defender Erotans](/npc/150291) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).



## Dialog

**You say:** `hail`



>**Defender Erotans says:** Nice to meet you, Soandso.  I keep watch over Shadowhaven from up here to make sure all is well.
end



## Combat

if Defender Erotans enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Erotans says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*