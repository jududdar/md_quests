# Defender Deralian


## Dialog

**You say:** `hail`



>**Defender Deralian says:** Hi there Soandso, welcome to the Fordel Quarter. I hope you enjoy your stay with us. If I can be of any help please let me know.
end



## Combat

if Defender Deralian enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Deralian says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*