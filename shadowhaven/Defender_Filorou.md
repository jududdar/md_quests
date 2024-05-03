# Defender Filorou


## Dialog

**You say:** `hail`



>**Defender Filorou says:** Greetings, Soandso. If you are just arriving in the city, I suggest that you go see the Trade Commissioner. Commissioner Henry is highly regarded in our city and is responsible for the continued success of the trade here.
end



## Combat

if Defender Filorou enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Filorou says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*