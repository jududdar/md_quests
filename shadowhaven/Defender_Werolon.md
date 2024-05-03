# Defender Werolon


## Dialog

**You say:** `hail`



>**Defender Werolon says:** Hi there Soandso, I'm debating whether or not to take a little break to check out the deals in the Bazaar. Do you think anyone will notice that I am gone? I do deserve a break ya know, I work pretty hard!
end



## Combat

if Defender Werolon enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Werolon says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*