# Defender Paegor
## Dialog

**You say:** `hail`



>**Defender Paegor says:** Good day to you Soandso, I hope you are having a splendid time in the Shadowhaven. If you are in search of that special magical item that you just cant seem to find in any of our stores make sure you visit the Bazaar. Take care.
end

## Combat

if Defender Paegor enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end

## Timer(s)

>**Defender Paegor says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!
## On NPC Death

**Stop timer** named *combatsay*