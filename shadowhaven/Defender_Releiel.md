# Defender Releiel



[Defender Releiel](/npc/150006) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).



## Dialog

**You say:** `hail`



>**Defender Releiel says:** Pleased to meet you, Soandso. I would love to chat but I am afraid I am currently on duty, should you have an urgent issue please see Daloran or Mistala Glimmerblade.
end



## Combat

if Defender Releiel enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Releiel says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*