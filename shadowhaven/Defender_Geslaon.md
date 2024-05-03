# Defender Geslaon


## Dialog

**You say:** `hail`



>**Defender Geslaon says:** Hello, Soandso, if you are here to conduct bank business please step inside and the banker will be with you as soon as possible.
end



## Combat

if Defender Geslaon enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Geslaon says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*