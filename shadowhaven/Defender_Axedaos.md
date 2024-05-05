# Defender Axedaos



[Defender Axedaos](/npc/150025) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).



## Dialog

**You say:** `hail`



>**Defender Axedaos says:** Greetings to you, Soandso. Beyond lies the path to Shadowhaven. I hope you enjoy your time with us.
end



## Combat

if Defender Axedaos enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Axedaos says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*