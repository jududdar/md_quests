# Defender Helodonea
## Dialog

**You say:** `hail`



>**Defender Helodonea says:** Welcome to House Fordel, Soandso.  It's great to meet you.
end

## Combat

if Defender Helodonea enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end

## Timer(s)

>**Defender Helodonea says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!
## On NPC Death

**Stop timer** named *combatsay*