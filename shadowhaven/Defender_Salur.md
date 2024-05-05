# Defender Salur



[Defender Salur](/npc/150038) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).



## Dialog

**You say:** `hail`



>**Defender Salur says:** Hello, Soandso, the path beyond leads to the bazaar as well as the commons area. If you are looking for a certain destination in particular please do not be afraid to ask.
end



## Combat

if Defender Salur enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Salur says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*