# Defender Lenduros

[Defender Lenduros](/npc/150008) is a level 55 Barbarian Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).

## Dialog
**You say:** `hail`

>**Defender Lenduros says:** Hail, Soandso. If you're looking for a refreshing beverage, then step right inside. My friend Barloten runs quite a tavern inside with plenty of interesting patrons.





## Combat
if Defender Lenduros enters combat  then
**Set a timer** named *combatsay* for 300 seconds
else
**Stop timer** named *combatsay*





## Timer(s)
>**Defender Lenduros says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!




## On NPC Death
**Stop timer** named *combatsay*
