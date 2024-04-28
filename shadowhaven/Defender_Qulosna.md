# Defender Qulosna
## Dialog

**You say:** `hail`



>**Defender Qulosna says:** Fine day in the Haven, is it not Soandso? I think this might be a nice time for a break at the tavern, if I don't say so myself.
end

## Combat

if Defender Qulosna enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end

## Timer(s)

>**Defender Qulosna says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!
## On NPC Death

**Stop timer** named *combatsay*