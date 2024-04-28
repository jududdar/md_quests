# Jilan Tollun
## Dialog

**You say:** `hail`



>**Jilan Tollun says:** Hello there. Please leave me alone I would like some peace and quiet.

**You say:** `armor`



>**Jilan Tollun says:** amben must have told you about the old beastlord we came upon. So tell me are you a worthy beastlord?

**You say:** `beastlord`



>**Jilan Tollun says:** Then you must want the armor I have. I have the veil, cape, gloves, talisman, belt, and claws.

**You say:** `belt`



>**Jilan Tollun says:** For the belt you must bring me a sky jewel, a mark of the wolf, an embedded steel figurine, and ancient wrappings.

**You say:** `cape`



>**Jilan Tollun says:** For the cape you must bring me a moon jewel, a mark of the panther, an iridescent crystal, and an embedded bronze figurine.

**You say:** `claw`



>**Jilan Tollun says:** For the claws you must bring me a meteor jewel, a mark of the bestial, an embedded adamantium figurine, and a roaring idol.

**You say:** `glove`



>**Jilan Tollun says:** For the gloves you must bring me a star jewel, a mark of the alligator, and embedded electrum figurine.

**You say:** `talisman`



>**Jilan Tollun says:** For the talisman you must bring me a cloud jewel, a mark of the shark, and an embedded silver figurine. 

**You say:** `veil`



>**Jilan Tollun says:** For the veil you must bring me a sun jewel, a mark of the tiger, and an embedded wooden figurine.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if **You turn in:** [Sky Jewel](/item/4492), [Embedded Steel Figurine](/item/5949), [Mark of the Wolf](/item/5948), [Ancient Wrappings](/item/5950)


FactionReward(e)


 **You receive:**  [Feral Belt](/item/3996) (+25000 exp)

elseif **You turn in:** [Moon Jewel](/item/4489), [Mark of the Panther](/item/5941), [Iridescent Crystal](/item/5942), [Embedded Bronze Figurine](/item/5943)


FactionReward(e)


 **You receive:**  [Feral Cape](/item/3993) (+25000 exp)

elseif **You turn in:** [Meteor Jewel](/item/4493), [Mark of the Bestial](/item/5951), [Embedded Admantium Figurine](/item/5952), [Roaring Idol](/item/5953)


FactionReward(e)


 **You receive:**  [Feral Claws](/item/3997) (+25000 exp)

elseif **You turn in:** [Star Jewel](/item/4490), [Mark of the Alligator](/item/5944), [Embedded Electrum Figurine](/item/5945)


FactionReward(e)


 **You receive:**  [Feral Gloves](/item/3994) (+25000 exp)

elseif **You turn in:** [Cloud Jewel](/item/4491), [Mark of the Shark](/item/5946), [Embedded Silver Figurine](/item/5947)


FactionReward(e)


 **You receive:**  [Feral Talisman](/item/3995) (+25000 exp)

elseif **You turn in:** [Sun Jewel](/item/4488), [Mark of the Tiger](/item/5939), [Embedded Wooden Figurine](/item/5940)


FactionReward(e)


 **You receive:**  [Feral Veil](/item/3992) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Jilan Tollun says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)