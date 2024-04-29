# Fabian
## Dialog

**You say:** `hail`




if( **Faction is** > Amiable) then



>**Fabian says:** Greetings, merry gentlefolk! If you enjoy the music, please feel free to cross my palm with gold.


else



>**Fabian says:** Oh look, a talking lump of refuse. How novel!

end

## Turn-Ins



local etched = 0;



if( **You turn in:** gold = 2) then


>**Fabian says:** Rat spittle! Busted another string! You seem like a good music loving citizen, could you please run to the Wind Spirit's Song and grab me a fresh set of lute strings?


e.other:Ding();





* __Faction:__ [League of Antonican Bards](/faction/284) (2)


* __Faction:__ [Knights of Truth](/faction/281) (1)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Ring of Scale](/faction/304) (-1)


* __Faction:__ [Mayong Mistmoore](/faction/285) (-1)

elseif( **You turn in:** [Lute Strings](/item/13709)) then 


>**Fabian says:** 'Many thanks, merry gentlefolk! Let me cross your palm in gratitude for your kindness. Hmmmm where did my lucky coin go?





* __Faction:__ [League of Antonican Bards](/faction/284) (2)


* __Faction:__ [Knights of Truth](/faction/281) (1)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Ring of Scale](/faction/304) (-1)


* __Faction:__ [Mayong Mistmoore](/faction/285) (-1)


if(math.random(1,3) == 3) then 



 **You receive:**  [An Etched Silver Coin](/item/13710) 



note = You only get the coin sometimes



 **You receive:** 0 (+5000 exp)

elseif( **You turn in:** [An Etched Silver Coin](/item/13710)) then 


>**Fabian says:** 'My lucky coin! How did it get in there? Well, never mind that. You are an honest person and although honesty is its own reward, I feel obligated to return the favor. Take this to Dionna if you enjoy music. Farewell friend!


* __Faction:__ [League of Antonican Bards](/faction/284) (2)


* __Faction:__ [Knights of Truth](/faction/281) (1)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Ring of Scale](/faction/304) (-1)


* __Faction:__ [Mayong Mistmoore](/faction/285) (-1)


 **You receive:**  [Note from Fabian](/item/13708) (+5000 exp)

**This NPC *should* return incorrect items given.**
