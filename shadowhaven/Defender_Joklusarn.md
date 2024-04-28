# Defender Joklusarn
## Dialog

**You say:** `hail`



>**Defender Joklusarn says:** Hail, Soandso. The path beyond leads to the Midst Quarter. Please be VERY careful when walking across this bridge, as it is quite easy to take a tumble.  I have seen many do just that and its not very pretty.
end

## Combat

if Defender Joklusarn enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end

## Timer(s)

>**Defender Joklusarn says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!
## On NPC Death

**Stop timer** named *combatsay*