# Defender Boyrslen


## Dialog

**You say:** `hail`



>**Defender Boyrslen says:** Hail, traveler. It's nice to have you with us in the Haven. Our city is a place of freedom and prosperity. Please respect all that we have accomplished when visiting and you will always be welcome.
end



## Combat

if Defender Boyrslen enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Boyrslen says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*