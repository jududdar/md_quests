# Legionnaire Eandalion
## Dialog

**You say:** `hail`



>**Legionnaire Eandalion says:** Salutations to you and your own. On your way to Katta are ya?

**You say:** `armor`



>**Legionnaire Eandalion says:** Frank must have told ya about the soldier's armor that we both keep to give to those worthy of wearing it. I have the mask, cloak, gauntlets, gorget, girdle, and swords.

**You say:** `cloak`



>**Legionnaire Eandalion says:** To get the cloak you will need to get me a meteor jewel, a mark of glory, a ring of wit, and some twilight fish scales.

**You say:** `gauntlets`



>**Legionnaire Eandalion says:** To get the gauntlets you will need to get me an astral jewel, a mark of opposition, and a hope quartz.

**You say:** `girdle`



>**Legionnaire Eandalion says:** To get the girdle you will need to get me a moon jewel, a mark of contention, a fire scorched stick, and a hope star ruby.

**You say:** `gorget`



>**Legionnaire Eandalion says:** To get the gorget you will need to get me a sun jewel, a mark of pride, and some star dust.

**You say:** `mask`



>**Legionnaire Eandalion says:** To get the mask you will need to get me a sky jewel, a mark of defiance, and a bag of scarlet sand.

**You say:** `sword`



>**Legionnaire Eandalion says:** To get the sword you will need to get me a star jewel, a mark of warfare, a hope fire opal, and some fire powder.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Meteor Jewel](/item/4493), [Mark of Glory](/item/5530), [Ring of Wit](/item/5584), [Twilight Fish Scales](/item/5585)) then 


FactionReward(e)


 **You receive:**  [Soldier's Cloak](/item/3941) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Mark of Opposition](/item/5586), [Hope Quartz](/item/5587)) then 


FactionReward(e)


 **You receive:**  [Soldier's Gauntlets](/item/3942) (+25000 exp)

elseif( **You turn in:** [Moon Jewel](/item/4489), [Mark of Contention](/item/5590), [Fire Scorched Stick](/item/5591), [Hope Star Ruby](/item/5592)) then 


FactionReward(e)


 **You receive:**  [Soldier's Girdle](/item/3944) (+25000 exp)

elseif( **You turn in:** [Sun Jewel](/item/4488), [Mark of Pride](/item/5588), [Star Dust](/item/5589)) then 


FactionReward(e)


 **You receive:**  [Soldier's Gorget](/item/3943) (+25000 exp)

elseif( **You turn in:** [Sky Jewel](/item/4492), [Mark of Defiance](/item/5528), [Bag of Scarlet Sand](/item/5529)) then 


FactionReward(e)


 **You receive:**  [Soldier's Mask](/item/3940) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Mark of Warfare](/item/5668), [Hope Fire Opal](/item/5669), [Fire Powder](/item/5677)) then 


FactionReward(e)


 **You receive:**  [Soldier's Long Sword](/item/3945) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Legionnaire Eandalion says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)