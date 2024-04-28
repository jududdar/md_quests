# Defender Nalout
## Dialog

**You say:** `hail`



>**Defender Nalout says:** Greetings, Soandso. Pleased to meet ya. I'd love to stay and chat, but then I wouldn't be keeping the city very safe while I'm talking to you would I?
end

## Combat

if Defender Nalout enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end

## Timer(s)

>**Defender Nalout says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!
## On NPC Death

**Stop timer** named *combatsay*