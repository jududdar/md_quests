# Defender Taglorns
## Dialog

**You say:** `hail`



>**Defender Taglorns says:** Hail, Soandso. Please form an orderly line and the banker will see you as soon as possible.
end

## Combat

if Defender Taglorns enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end

## Timer(s)

>**Defender Taglorns says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!
## On NPC Death

**Stop timer** named *combatsay*