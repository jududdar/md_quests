# Defender Gerlinson


## Dialog

**You say:** `hail`



>**Defender Gerlinson says:** Hello, Soandso, and welcome to Shadowhaven.  There is much that lies inside to be seen so I will not keep you waiting. Good luck to you.
end



## Combat

if Defender Gerlinson enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Gerlinson says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*