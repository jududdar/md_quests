# Defender Eronlo
## Dialog

**You say:** `hail`



>**Defender Eronlo says:** Lo dere, Soandso.  Da Shadowhaven can be a confusin place at times, but it can be quite easy to git around once ya know what quarter you are in. The city consists of four of these quarters being da Commons quarter which is here, along with the House of Stout, House of Fordel and House of Midst.
end

## Combat

if Defender Eronlo enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end

## Timer(s)

>**Defender Eronlo says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!
## On NPC Death

**Stop timer** named *combatsay*