# Trallen Grimhammer
## Dialog

**You say:** `hail`



>**Trallen Grimhammer says:** Greetings and well met Soandso. Don't listen to ol' Latrag over there he'll never stop brewin' the best durn ale to be found.

**You say:** `boots`



>**Trallen Grimhammer says:** For the boots yer gonna have to get me a sun jewel. a mark of destiny. and a fleshy vine.

**You say:** `armor`



>**Trallen Grimhammer says:** Latrag is goin' on 'bout his armor again isn't he. Well friend be ye a paladin?

**You say:** `paladin`



>**Trallen Grimhammer says:** Of course ya are Soandso. Why would have ya asked me about the armor if ye wasn't eh. I have the boots, mask, cloak, gauntlets, gorget, girdle, and a sword. Which do ye want?

**You say:** `mask`



>**Trallen Grimhammer says:** For the mask yer gonna have to get me a moon jewel, a mark of blessings, and some crystallized dew.

**You say:** `cloak`



>**Trallen Grimhammer says:** For the cloak yer gonna have to get me a star jewel, a mark of the steadfast, a lexicon of the sun, and some glade dew.

**You say:** `gauntlets`



>**Trallen Grimhammer says:** For the gauntlets yer gonna have to get me a cloud jewel, a mark of honor, and some naturally formed quartz.

**You say:** `gorget`



>**Trallen Grimhammer says:** For the gorget yer gonna have to get me a sky jewel, a mark of gallantry, and a lunar marked stone.

**You say:** `girdle`



>**Trallen Grimhammer says:** For the girdle yer gonna have to get me a meteor jewel, a mark of heart, a lexicon of the moon, and a dread leech eye.

**You say:** `sword`



>**Trallen Grimhammer says:** For the sword yer gonna have to get me an astral jewel, a mark of the noble, a hardened clay sculpture, and a runic ear plug.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Sun Jewel](/item/4488), [Mark of Destiny](/item/5904), [Fleshy Vine](/item/5905)) then 


FactionReward(e)


 **You receive:**  [Blessed Knight's Boots](/item/3978) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Mark of the Steadfast](/item/5908), [Lexicon of the Sun](/item/5909), [Glade Dew](/item/5910)) then 


FactionReward(e)


 **You receive:**  [Blessed Knight's Cloak](/item/3980) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Mark of Honor](/item/5911), [Naturally Formed Quartz](/item/5912)) then 


FactionReward(e)


 **You receive:**  [Blessed Knight's Gauntlets](/item/3981) (+25000 exp)

elseif( **You turn in:** [Meteor Jewel](/item/4493), [Mark of Heart](/item/5915), [Lexicon of the Moon](/item/5916), [Dread Leech Eye](/item/5917)) then 


FactionReward(e)


 **You receive:**  [Blessed Knight's Girdle](/item/3983) (+25000 exp)

elseif( **You turn in:** [Sky Jewel](/item/4492), [Mark of Gallantry](/item/5913), [Lunar Marked Stone](/item/5914)) then 


FactionReward(e)


 **You receive:**  [Blessed Knight's Gorget](/item/3982) (+25000 exp)

elseif( **You turn in:** [Moon Jewel](/item/4489), [Mark of Blessings](/item/5906), [Crystallized Dew](/item/5907)) then 


FactionReward(e)


 **You receive:**  [Blessed Knight's Mask](/item/3979) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Mark of the Noble](/item/5918), [Hardened Clay Sculpture](/item/5919), [Runic Ear Plug](/item/5920)) then 


FactionReward(e)


 **You receive:**  [Blessed Knight's Defender](/item/3984) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Trallen Grimhammer says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)