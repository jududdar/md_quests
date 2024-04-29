# Tamben Prinon
## Dialog

**You say:** `hail`



>*Tamben Prinon looks over you examining you from head to toe. 'Ye have the look of an adventurer. I have a tale to tell if you would like to hear it.*

**You say:** `tale`



>**Tamben Prinon says:** Years ago I and Jilan were traveling around the far reaches of this land. One day we came upon an old vah shir who was injured in the mountains. He implored us to help him. Do you wish me to continue?

**You say:** `continue`



>**Tamben Prinon says:** As I was saying this old vah shir required assistance.  We bound his wounds and he asked us to take his armor and give it to a Beastlord worthy of wearing it.  Are you a worthy beastlord?

**You say:** `cap`



>**Tamben Prinon says:** For the cap you must prove your worth. Go gather up a sun jewel, a mark of feral spirits, an embedded copper figurine, and a frosted stone.

**You say:** `tunic`



>**Tamben Prinon says:** For the tunic you must prove your worth. Go gather up a moon jewel, a mark of animal spirits, a silver gilded bracelet, and an embedded mithril figurine.

**You say:** `sleeves`



>**Tamben Prinon says:** For the sleeves you must prove your worth. Go gather a star jewel, a mark of wild spirits, an embedded clay figurine, and a furrowed carving.

**You say:** `leggings`



>**Tamben Prinon says:** For the leggings you must prove your worth. Go gather a cloud jewel, a mark of natural spirits, an embedded stone figurine, and a blue moonstone.

**You say:** `mantle`



>**Tamben Prinon says:** For the mantle you must prove your worth. Go gather a sky jewel, a mark of wilderness, and an embedded platinum figurine.

**You say:** `bracer`



>**Tamben Prinon says:** For the bracer you must prove your worth. Go gather a meteor jewel, a mark of animal training, and an embedded brass figurine.

**You say:** `boots`



>**Tamben Prinon says:** For the boots you must prove your worth. Go gather an astral jewel, a mark of beast mastery, and an embedded gold figurine.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Sun Jewel](/item/4488), [Mark of Feral Spirits](/item/5921), [Embedded Copper Figurine](/item/5927), [Frosted Stone](/item/5928)) then


FactionReward(e)


 **You receive:**  [Feral Cap](/item/3985) (+25000 exp)

elseif( **You turn in:** [Moon Jewel](/item/4489), [Mark of Animal Spirits](/item/5929), [Silver Gilded Bracelet](/item/5922), [Embedded Mithril Figurine](/item/5923)) then


FactionReward(e)


 **You receive:**  [Feral Tunic](/item/3986) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Embedded Clay Figurine](/item/5925), [Mark of Wild Spirits](/item/5924), [Furrowed Carving](/item/5926)) then


FactionReward(e)


 **You receive:**  [Feral Sleeves](/item/3987) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Mark of Natural Spirits](/item/5930), [Embedded Stone Figurine](/item/5931), [Blue Moonstone](/item/5932)) then


FactionReward(e)


 **You receive:**  [Feral Leggings](/item/3988) (+25000 exp)

elseif( **You turn in:** [Sky Jewel](/item/4492), [Mark of Wilderness](/item/5933), [Embedded Platinum Figurine](/item/5934)) then


FactionReward(e)


 **You receive:**  [Feral Mantle](/item/3989) (+25000 exp)

elseif( **You turn in:** [Meteor Jewel](/item/4493), [Mark of Animal Training](/item/5935), [Embedded Brass Figurine](/item/5936)) then


FactionReward(e)


 **You receive:**  [Feral Bracer](/item/3990) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Mark of Beast Mastery](/item/5937), [Embedded Gold Figurine](/item/5938)) then


FactionReward(e)


 **You receive:**  [Feral Boots](/item/3991) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Tamben Prinon says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)