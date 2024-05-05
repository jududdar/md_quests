# Defender Derlsin



[Defender Derlsin](/npc/150292) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).



## Dialog

**You say:** `hail`



>**Defender Derlsin says:** Greetings, Soandso. Beyond these doors is the Fordel Armory. It is here that the Fordel Defenders are outfitted with the necessary armor to complete the basic training necessary to guard Shadowhaven.
end



## Combat

if Defender Derlsin enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Derlsin says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*