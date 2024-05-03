# Defender Tamalre


## Dialog

**You say:** `hail`



>**Defender Tamalre says:** Hello, Soandso, I am an archer of the Fordel. I represent the first line of defense shall the Haven ever be invaded.
end



## Combat

if Defender Tamalre enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Tamalre says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*