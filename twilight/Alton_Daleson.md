# Alton Daleson
## Dialog

**You say:** `hail`



>**Alton Daleson says:** Welcome to Jern's Rest!  I'm the owner and proprietor of this inn, it's been in my family for generations.  My great grandaddy, Jern, built it back when Katta Castellum was first being built.  If ya be wantin' of anything don't hesitate to ask.

**You say:** `armor`



>**Alton Daleson says:** His armor has also been in the family for generations, if ye be a [ranger] I don't have much use for it running this inn. I'll just need something in return for it.
  
**You say:** `ranger`



>**Alton Daleson says:** Excellent! If you are interested I have the Woodsman's [Helm], Woodsmand's [Mail], Woodsman's [Vambraces], Woodsman's [Greaves], Woodsman's [Bracer], Woodsman's [Boots], and the Woodsman's [Axe]. If youa re interested in the rest of his armor you'll have to ask my wife Ellen, she'll have some errands you can run for her.
  
**You say:** `axe`



>**Alton Daleson says:** If you want the Woodsman's Axe you will have to aquire these items: a sun jewel, a mark of the naturalist, some ancient pottery, and a fossilized skull.
  
**You say:** `boots`



>**Alton Daleson says:** If you want the Woodsman's Boots you will have to acquire these items: a star jewel, a mark of timber, and a gilded steel rod.
  
**You say:** `bracer`



>**Alton Daleson says:** If you want the Woodsman's Bracer you will have to acquire these items: a moon jewel, a mark of lakes, and some lightning dust.
  
**You say:** `greaves`



>**Alton Daleson says:** If you want the Woodsman's Greaves you will have to acquire these items: an astral jewel, a mark of oceans, a pouch of fire stones, and a cat skin pouch.
  
**You say:** `helm`



>**Alton Daleson says:** For the Woodsman's Helm you will have to acquire these items: a cloud jewel, a mark of leaves, a frost covered leaf, and some sea grass.
  
**You say:** `mail`



>**Alton Daleson says:** To get the Woodsman's Mail you will have to acquire these items: a sky jewel, a mark of forests, a frozen vial, and a tro jeg brain.
  
**You say:** `vambraces`



>**Alton Daleson says:** If you want the Woodsman's Vambraces you will have to acquire these items: a meteor jewel, a mark of mountains, a tro jeg eye, and a solstice rune.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Ancient Pottery](/item/5852), [Fossilized Skull](/item/5853), [Mark of the Naturalist](/item/5851), [Sun Jewel](/item/4488)) then 


FactionReward(e)


 **You receive:**  [Woodsman's Axe](/item/3958) (+25000 exp)

elseif( **You turn in:** [Gilded Steel Rod](/item/5695), [Mark of Timber](/item/5694), [Star Jewel](/item/4490)) then 


FactionReward(e)


 **You receive:**  [Woodsman's Boots](/item/3952) (+25000 exp)

elseif( **You turn in:** [Lightning Dust](/item/5693), [Mark of Lakes](/item/5692), [Moon Jewel](/item/4489)) then 


FactionReward(e)


 **You receive:**  [Woodsman's Bracer](/item/3951) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Cat Skin Pouch](/item/5689), [Mark of Oceans](/item/5687), [Pouch of Fire Stones](/item/5688)) then 


FactionReward(e)


 **You receive:**  [Woodsman's Greaves](/item/3949) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Frost Covered Leaf](/item/5679), [Mark of Leaves](/item/5678), [Sea Grass](/item/5680)) then 


FactionReward(e)


 **You receive:**  [Woodsman's Coif](/item/3946) (+25000 exp)

elseif( **You turn in:** [Frozen Vial](/item/5682), [Mark of Forests](/item/5681), [Sky Jewel](/item/4492), [Tro Jeg Brain](/item/5683)) then 


FactionReward(e)


 **You receive:**  [Woodsman's Mail](/item/3947) (+25000 exp)

elseif( **You turn in:** [Mark of Mountains](/item/5684), [Meteor Jewel](/item/4493), [Solstice Rune](/item/5686), [Tro Jeg Eye](/item/5685)) then 


FactionReward(e)


 **You receive:**  [Woodsman's Vambraces](/item/3948) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Alton Daleson says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)
