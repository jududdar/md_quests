# Defender Jolusnan



[Defender Jolusnan](/npc/150019) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).



## Dialog

**You say:** `hail`



>**Defender Jolusnan says:** Greetings, Soandso. I am in a great hurry and cannot be led astray from my patrolling duties. Good luck to you.
end



## Combat

if Defender Jolusnan enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Jolusnan says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*