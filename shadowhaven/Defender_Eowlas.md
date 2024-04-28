# Defender Eowlas
## Dialog

**You say:** `hail`



>**Defender Eowlas says:** Hello there. You're looking to make a deposit are you?  Well then those guys over there are who you want to see. Bankers aren't usually as armed as I am, unless of course your payment is extremely late.
end

## Combat

if Defender Eowlas enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end

## Timer(s)

>**Defender Eowlas says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!
## On NPC Death

**Stop timer** named *combatsay*