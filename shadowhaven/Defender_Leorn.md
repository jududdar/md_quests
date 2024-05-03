# Defender Leorn


## Dialog

**You say:** `hail`



>**Defender Leorn says:** Welcome to the Fordel Quarter Soandso, If you are heading in further please watch your step. Some drunk came through and dropped a bottle right on the steps.  We have someone already on the way to clean it up just wanted to make sure nobody stepped on it.
end



## Combat

if Defender Leorn enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Leorn says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*