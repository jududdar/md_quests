# Defender Zaerel


## Dialog

**You say:** `hail`



>**Defender Zaerel says:** Hello, Soandso, it is a pleasure to meet you. If you are an aspiring tradesman then the Bazaar is right up your alley! Just follow these steps here to enter the Bazaar and have a great time!
end



## Combat

if Defender Zaerel enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Zaerel says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*