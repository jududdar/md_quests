# Defender Naetel


## Dialog

**You say:** `hail`



>**Defender Naetel says:** Greetings to you, Soandso. I welcome you to the finest and most prosperous city in all of Luclin. Please enjoy your stay with us in the Shadowhaven.
end



## Combat

if Defender Naetel enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Naetel says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*