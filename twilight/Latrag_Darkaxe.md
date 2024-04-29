# Latrag Darkaxe
## Dialog

**You say:** `hail`



>*Latrag Darkaxe lets out a resounding belch. 'Har there lad! Ye be sure 'nuff to tell em all that Brewmaster Latrag is retiring.'*

**You say:** `retiring`



>**Latrag Darkaxe says:** Ya got that right. I'm goin' to concentrate more on me devotion to Brell as a holy knight!

**You say:** `knight`



>**Latrag Darkaxe says:** I be a paladin of Brell thar Soandso. Might ye be a paladin yerself?

**You say:** `paladin`



>**Latrag Darkaxe says:** That's good. Ya know I have some armor ye might be interested in.

**You say:** `armor`



>**Latrag Darkaxe says:** Yar! I have me a helm, breastplate, vambraces, greaves, pauldrons, and a bracer. If ye want the rest talk to the mighty holy warrior Trallen over there about armor.

**You say:** `breastplate`



>**Latrag Darkaxe says:** For the breastplate ye gotta bring me a star jewel, a mark of courage, a white marble bowl, and a jagged reed.

**You say:** `vambrace`



>**Latrag Darkaxe says:** For the vambraces ye gotta bring me a cloud jewel, a mark of righteousness, a runed card, and a pristine ebony idol

**You say:** `greaves`



>**Latrag Darkaxe says:** For the greaves ye gotta bring me a sky jewel, a mark of bravery, a sunflower fruit, and a weathered bundle of wood

**You say:** `pauldrons`



>**Latrag Darkaxe says:** For the pauldrons ye gotta bring me a meteor jewel, a mark of daring, and a life gem.

**You say:** `bracer`



>**Latrag Darkaxe says:** For the bracer ye gotta bring me an astral jewel, a mark of reliance, and some blessed water

**You say:** `helm`



>**Latrag Darkaxe says:** For the helm ye gotta bring me a moon jewel, a mark of valor, a withered branch, and a pale pearl.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Astral Jewel](/item/4494), [Mark of Reliance](/item/5902), [Blessed Water](/item/5903)) then 


FactionReward(e)


 **You receive:**  [Blessed Knight's Bracer](/item/3977) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Mark of Courage](/item/5891), [White Marble Bowl](/item/5892), [Jagged Reed](/item/5893)) then 


FactionReward(e)


 **You receive:**  [Blessed Knight's Breastplate](/item/3973) (+25000 exp)

elseif( **You turn in:** [Sky Jewel](/item/4492), [Mark of Bravery](/item/5897), [Sunflower Fruit](/item/5898), [Weathered Bundle of Wood](/item/5899)) then 


FactionReward(e)


 **You receive:**  [Blessed Knight's Greaves](/item/3975) (+25000 exp)

elseif( **You turn in:** [Moon Jewel](/item/4489), [Mark of Valor](/item/5888), [Withered Branch](/item/5889), [Pale Pearl](/item/5890)) then 


FactionReward(e)


 **You receive:**  [Blessed Knight's Helm](/item/3972) (+25000 exp)

elseif( **You turn in:** [Meteor Jewel](/item/4493), [Mark of Daring](/item/5900), [Life Gem](/item/5901)) then 


FactionReward(e)


 **You receive:**  [Blessed Knight's Pauldrons](/item/3976) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Mark of Righteousness](/item/5894), [Runic Card](/item/5895), [Pristine Ebony Idol](/item/5896)) then 


FactionReward(e)


 **You receive:**  [Blessed Knight's Vambraces](/item/3974) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Latrag Darkaxe says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)