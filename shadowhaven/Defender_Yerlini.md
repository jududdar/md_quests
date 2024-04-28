# Defender Yerlini
## Dialog

**You say:** `hail`



>**Defender Yerlini says:** Hi there. I am one of the finest archers in the Haven so they have me keep watch from up top.
end

## Combat

if Defender Yerlini enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end

## Timer(s)

>**Defender Yerlini says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!
## On NPC Death

**Stop timer** named *combatsay*