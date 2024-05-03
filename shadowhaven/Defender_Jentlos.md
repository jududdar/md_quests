# Defender Jentlos


## Dialog

**You say:** `hail`



>**Defender Jentlos says:** Hi dere Soandso, it sure is a big city we got here, so if ya get lost at any time make sure you ask somebuddy where to get where yer tryin to go!
end



## Combat

if Defender Jentlos enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Jentlos says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*