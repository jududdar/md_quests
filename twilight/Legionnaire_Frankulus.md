# Legionnaire Frankulus
## Dialog

**You say:** `hail`



>*Legionnaire Frankulus sighs and looks at you. 'Another traveler to our fair city of Katta Castellum, you be careful now.'*

**You say:** `armor`



>**Legionnaire Frankulus says:** Yes I am one of the keepers of the soldier's armor. The pieces I have are the helm, breastplate, vambraces, greaves, pauldrons, bracer, and boots. Eandalion keeps the other pieces just ask him about armor.

**You say:** `boots`



>**Legionnaire Frankulus says:** For the boots you will have to bring to me a cloud jewel, a mark of the martial, and a hope ruby.

**You say:** `bracer`



>**Legionnaire Frankulus says:** For the bracer you will have to bring to me a star jewel, a mark of the siege, and a blue egg.

**You say:** `breastplate`



>**Legionnaire Frankulus says:** For the breastplate you will have to bring to me a meteor jewel, a mark of war, a weathered yew wand, and some dew of dawn.

**You say:** `greaves`



>**Legionnaire Frankulus says:** For the greaves you will have to bring to me a sun jewel, a mark of archery, a golden torch, and a small meteor fragment.

**You say:** `helm`



>**Legionnaire Frankulus says:** For the helm you will have to bring to me a sky jewel, a mark of battle, some petrified toes, and a fire blossom.

**You say:** `pauldrons`



>**Legionnaire Frankulus says:** For the pauldrons you will have to bring to me a moon jewel, a mark of swordsmanship, and a water blossom.

**You say:** `vambraces`



>**Legionnaire Frankulus says:** For the vambraces you will have to bring to me an astral jewel, a mark of arms, a small sponge, and a scorched rock.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Cloud Jewel](/item/4491), [Mark of the Martial](/item/5496), [Hope Ruby](/item/5497)) then 


FactionReward(e)


 **You receive:**  [Soldier's Boots](/item/3939) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Mark of the Siege](/item/5494), [Blue Egg](/item/5495)) then 


FactionReward(e)


 **You receive:**  [Soldier's Bracer](/item/3938) (+25000 exp)

elseif( **You turn in:** [Meteor Jewel](/item/4493), [Mark of War](/item/5483), [Weathered Yew Wand](/item/5484), [Dew of Dawn](/item/5485)) then 


FactionReward(e)


 **You receive:**  [Soldier's Breastplate](/item/3934) (+25000 exp)

elseif( **You turn in:** [Sun Jewel](/item/4488), [Mark of Archery](/item/5489), [Golden Torch](/item/5490), [Small Meteor Fragment](/item/5491)) then 


FactionReward(e)


 **You receive:**  [Soldier's Greaves](/item/3936) (+25000 exp)

elseif( **You turn in:** [Sky Jewel](/item/4492), [Mark of Battle](/item/5480), [Petrified Toes](/item/5481), [Fire Blossom](/item/5482)) then 


FactionReward(e)


 **You receive:**  [Soldier's Helm](/item/3933) (+25000 exp)

elseif( **You turn in:** [Moon Jewel](/item/4489), [Mark of Swordsmanship](/item/5492), [Water Blossom](/item/5493)) then 


FactionReward(e)


 **You receive:**  [Soldier's Pauldrons](/item/3937) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Mark of Arms](/item/5486), [Small Sponge](/item/5487), [Scorched Rock](/item/5488)) then 


FactionReward(e)


 **You receive:**  [Soldier's Vambraces](/item/3935) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Legionnaire Frankulus says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)