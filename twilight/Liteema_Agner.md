# Liteema Agner
## Dialog

**You say:** `hail`



>*Liteema Agner looks up and smiles.  'Hiya. I just love fishing, don't you?'*

**You say:** `armor`



>**Liteema Agner says:** Oh! Tolli sent you over here didn't he. If you're a rogue and want some armor just let me know.

**You say:** `rogue`



>**Liteema Agner says:** This stuff isn't free no sir! I have a mask. cloak. gauntlets. gorget. waistband. and a dirk.  Just ask and I'll tell ya what ya have to do to get it.

**You say:** `mask`



>**Liteema Agner says:** For the mask of concealment you're going to have to go get me an astral jewel, a mark of deceit, and an engraved fire opal statuette.

**You say:** `cloak`



>**Liteema Agner says:** For the cloak of concealment you're going to have to go get me a sun jewel, a mark of secrecy, an engraved ivory statuette, and a polished gemstone.

**You say:** `gauntlets`



>**Liteema Agner says:** For the gauntlets of concealment you're going to have to go get me a moon jewel, a mark of deception, and an engraved gold statuette.

**You say:** `gorget`



>**Liteema Agner says:** For the gorget of concealment you're going to have to go get me a star jewel, a mark of trickery, and an engraved wooden statuette.

**You say:** `waistband`



>**Liteema Agner says:** For the waistband of concealment you're going to have to go get me a cloud jewel, a mark of silence, an engraved platinum statuette, and a true silver needle.

**You say:** `dirk`



>**Liteema Agner says:** For the dirk of concealment you're going to have to go get me a sky jewel, a mark of greed, an engraved mithril statuette, and a dread hilt.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Astral Jewel](/item/4494), [Mark of Deceit](/item/5287), [Engraved Fire Opal Statuette](/item/5288)) then 


FactionReward(e)


 **You receive:**  [Mask of Concealment](/item/3795) (+25000 exp)

elseif( **You turn in:** [Sun Jewel](/item/4488), [Mark of Secrecy](/item/5289), [Engraved Ivory Statuette](/item/5290), [Polished Gemstone](/item/5291)) then 


FactionReward(e)


 **You receive:**  [Cloak of Concealment](/item/3796) (+25000 exp)

elseif( **You turn in:** [Moon Jewel](/item/4489), [Mark of Deception](/item/5292), [Engraved Gold Statuette](/item/5293)) then 


FactionReward(e)


 **You receive:**  [Gauntlets of Concealment](/item/3797) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Mark of Trickery](/item/5294), [Engraved Wooden Statuette](/item/5295)) then 


FactionReward(e)


 **You receive:**  [Gorget of Concealment](/item/3798) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Mark of Silence](/item/5285), [Engraved Platinum Statuette](/item/5297), [True Silver Needle](/item/5298)) then 


FactionReward(e)


 **You receive:**  [Girdle of Concealment](/item/3799) (+25000 exp)

elseif( **You turn in:** [Sky Jewel](/item/4492), [Mark of Greed](/item/5299), [Engraved Mithril Statuette](/item/5326), [Dread Hilt](/item/5327)) then 


FactionReward(e)


 **You receive:**  [Dirk of Concealment](/item/3800) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Liteema Agner says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)