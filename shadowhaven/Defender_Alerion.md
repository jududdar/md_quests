# Defender Alerion


## Dialog

**You say:** `hail`



>**Defender Alerion says:** Glad to know you, Soandso.  Please do your best to watch your step around this pool.  It has been nice to see so many new faces around the city, but many has been the time that I have had to dive in after someone and, to be honest, I am not the greatest swimmer in all the world- now with all of the extra traffic, I get a bit nervous.
end



## Combat

if Defender Alerion enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Alerion says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*