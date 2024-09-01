# Defender Geslaon

[Defender Geslaon](/npc/150297) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).

## Dialog
**You say:** `hail`

>**Defender Geslaon says:** Hello, Soandso, if you are here to conduct bank business please step inside and the banker will be with you as soon as possible.





## Combat
if Defender Geslaon enters combat  then
**Set a timer** named *combatsay* for 300 seconds
else
**Stop timer** named *combatsay*





## Timer(s)
>**Defender Geslaon says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!




## On NPC Death
**Stop timer** named *combatsay*
