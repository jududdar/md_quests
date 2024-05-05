# Defender Wemblen



[Defender Wemblen](/npc/150141) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).



## Dialog

**You say:** `hail`



>**Defender Wemblen says:** Hail, Soandso. No time for chitchat, I'm afraid.  I have many house checks to do today.
end



## Combat

if Defender Wemblen enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Wemblen says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*