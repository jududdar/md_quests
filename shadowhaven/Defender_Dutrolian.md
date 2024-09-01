# Defender Dutrolian

[Defender Dutrolian](/npc/150028) is a level 55 Barbarian Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).

## Dialog
**You say:** `hail`

>**Defender Dutrolian says:** Hey there Soandso, if you are leaving the Haven to go trade in the Bazaar, I hope you have a wonderful and prosperous day! Make sure you come back and visit soon.





## Combat
if Defender Dutrolian enters combat  then
**Set a timer** named *combatsay* for 300 seconds
else
**Stop timer** named *combatsay*





## Timer(s)
>**Defender Dutrolian says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!




## On NPC Death
**Stop timer** named *combatsay*
