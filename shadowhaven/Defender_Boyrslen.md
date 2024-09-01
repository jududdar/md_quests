# Defender Boyrslen

[Defender Boyrslen](/npc/150287) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).



## Dialog

**You say:** `hail`


>**Defender Boyrslen says:** Hail, traveler. It's nice to have you with us in the Haven. Our city is a place of freedom and prosperity. Please respect all that we have accomplished when visiting and you will always be welcome.









## Combat

if Defender Boyrslen enters combat  then

**Set a timer** named *combatsay* for 300 seconds

else

**Stop timer** named *combatsay*









## Timer(s)

>**Defender Boyrslen says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!







## On NPC Death

**Stop timer** named *combatsay*

