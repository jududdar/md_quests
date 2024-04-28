# Defender Polosnes
## Dialog

**You say:** `hail`



>**Defender Polosnes says:** How do you do Soandso. Beyond these steps is the Fordel Quarter. Enjoy your stay with us.
end

## Combat

if Defender Polosnes enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end

## Timer(s)

>**Defender Polosnes says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!
## On NPC Death

**Stop timer** named *combatsay*