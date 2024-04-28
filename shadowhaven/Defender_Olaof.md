# Defender Olaof
## Dialog

**You say:** `hail`



>**Defender Olaof says:** Hello, I am Olaof, I am an aspiring musician, you know. For now I am just a Defender, one of the many. It was nice to meet you and I hope you enjoy your stay.
end

## Combat

if Defender Olaof enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end

## Timer(s)

>**Defender Olaof says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!
## On NPC Death

**Stop timer** named *combatsay*