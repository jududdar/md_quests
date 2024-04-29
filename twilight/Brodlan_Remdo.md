# Brodlan Remdo
## Dialog

**You say:** `hail`



>**Brodlan Remdo says:** Why hello, I'm in charge of the fishing operations here on Jern's Isle.  [Fish] are my area of expertise.

**You say:** `fish`



>**Brodlan Remdo says:** We have fish come in here all the time. Sometimes we catch an [oddity] now and again.

**You say:** `oddity`



>**Brodlan Remdo says:** Once we pulled up this ancient chest filled with this [dark plate armor].

**You say:** `armor`



>**Brodlan Remdo says:** Looked the like kind of armor a dark knight would wear. if ya want it I'm sure we could arrange a [trade] of some sort.

**You say:** `trade`



>**Brodlan Remdo says:** Since Trevor and I are the ones that found it we split it between ourselves. I have a [helm], [breastplate], [vambraces], [greaves], [pauldrons], [bracer], and [boots]. Ask Trevor about the rest of the armor.

**You say:** `breastplate`



>**Brodlan Remdo says:** For the darkened knight's breastplate fetch me a cloud jewel. a mark of fear. a delicate glass sculpture. and a painted ornament.

**You say:** `vambraces`



>**Brodlan Remdo says:** For the darkened knight's vambraces fetch me a sky jewel. a mark of terror. a runed ornamental mace. and an ancient tablet.

**You say:** `greaves`



>**Brodlan Remdo says:** For the darkened knight's greaves fetch me a meteor jewel. a mark of dread. the King's Tome. and a polished ivory idol.

**You say:** `pauldrons`



>**Brodlan Remdo says:** For the darkened knight's pauldrons fetch me an astral jewel. a mark of hatred. and an ancient petrified tulip.

**You say:** `bracer`



>**Brodlan Remdo says:** For the darkened knight's bracer fetch me a sun jewel. a mark of intimidation. and a small rough marble figurine.

**You say:** `boots`



>**Brodlan Remdo says:** For the darkened knight's boots fetch me a moon jewel. a mark of horror. and a fanged talisman.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Moon Jewel](/item/4489), [Mark of Horror](/item/5871), [Fanged Talisman](/item/5872)) then 


FactionReward(e)


 **You receive:**  [Darkened Knight's Boots](/item/3965) (+25000 exp)

elseif( **You turn in:** [Sun Jewel](/item/4488), [Mark of Intimidation](/item/5869), [Small Rough Marble Figurine](/item/5870)) then 


FactionReward(e)


 **You receive:**  [Darkened Knight's Bracer](/item/3964) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Mark of Fear](/item/5857), [Delicate Glass Sculpture](/item/5860), [Painted Ornament](/item/5859)) then 


FactionReward(e)


 **You receive:**  [Darkened Knight's Breastplate](/item/3960) (+25000 exp)

elseif( **You turn in:** [Meteor Jewel](/item/4493), [Mark of Dread](/item/5864), [King's Tome](/item/5865), [Polished Ivory Idol](/item/5866)) then 


FactionReward(e)


 **You receive:**  [Darkened Knight's Greaves](/item/3962) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Mark of Shadows](/item/5854), [Primitive Totem](/item/5855), [Golden Spoon](/item/5856)) then 


FactionReward(e)


 **You receive:**  [Darkened Knight's Helm](/item/3959) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Mark of Dark Fate](/item/5873), [Crystalline Idol](/item/5874)) then 


FactionReward(e)


 **You receive:**  [Darkened Knight's Mask](/item/3966) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Mark of Hatred](/item/5867), [Ancient Petrified Tulip](/item/5868)) then 


FactionReward(e)


 **You receive:**  [Darkened Knight's Pauldrons](/item/3963) (+25000 exp)

elseif( **You turn in:** [Sky Jewel](/item/4492), [Mark of Terror](/item/5861), [Runed Ornamental Mace](/item/5862), [Ancient Tablet](/item/5863)) then 


FactionReward(e)


 **You receive:**  [Darkened Knight's Vambraces](/item/3961) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Brodlan Remdo says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)