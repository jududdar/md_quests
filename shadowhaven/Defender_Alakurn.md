# Defender Alakurn


## Dialog

**You say:** `hail`



>**Defender Alakurn says:** Hail, Soandso. Are you leaving the Haven?  If so, be sure to visit soon and see how our city continues to prosper more and more with the passing days.
end



## Combat

if Defender Alakurn enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Alakurn says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*