# Defender Rogalo


## Dialog

**You say:** `hail`



>**Defender Rogalo says:** Hello there, Soandso, I hope you found everything that you were looking for in the commons. These steps will take you to the Fordel Quarter.
end



## Combat

if Defender Rogalo enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Rogalo says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*