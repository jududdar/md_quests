# Defender Alroklon
## Dialog

**You say:** `hail`



>**Defender Alroklon says:** Hail and well met, Soandso. It is a pleasure to have you in Shadowhaven.  Should you venture up these stairs, you will find yourself in the Fordel Quarter. Good luck to you, traveler.
end

## Combat

if Defender Alroklon enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end

## Timer(s)

>**Defender Alroklon says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!
## On NPC Death

**Stop timer** named *combatsay*