# Defender Dalivayen
## Dialog

**You say:** `hail`



>**Defender Dalivayen says:** Pleased to meet you, Soandso.  These stairs will take you to the training ground for new Shadowhaven Defenders recruits. Please be careful when in the training area, we wouldn't want to have any unfortunate accidents.
end

## Combat

if Defender Dalivayen enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end

## Timer(s)

>**Defender Dalivayen says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!
## On NPC Death

**Stop timer** named *combatsay*