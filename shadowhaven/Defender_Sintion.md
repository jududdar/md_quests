# Defender Sintion


## Dialog

**You say:** `hail`



>**Defender Sintion says:** I welcome you to the Midst Quarter Soandso, if there is anything that I can provide to aid you in your studies please let me know.
end



## Combat

if Defender Sintion enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Sintion says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*