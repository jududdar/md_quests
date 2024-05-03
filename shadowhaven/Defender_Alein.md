# Defender Alein


## Dialog

**You say:** `hail`



>**Defender Alein says:** Welcome to Shadow Haven, adventurer. You are entering the Fordel Quarter.
end



## Combat

if Defender Alein enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Alein says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*