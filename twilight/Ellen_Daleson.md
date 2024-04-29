# Ellen Daleson
## Dialog

**You say:** `hail`



>**Ellen Daleson says:** Oh hello there. I'm in charge of the docks here and wife to Alton.

**You say:** `alton`



>**Ellen Daleson says:** My husband is the owner of Jern's Rest. It's been his family for ages ever since his great grandaddy Jern built it.

**You say:** `ranger`



>**Ellen Daleson says:** Very well. If you want the Woodsman's [Mantle], Woodsman's [Mask], Woodsman's [Cape], Woodsman's [Guantlets], Woodsman's [Choker], or Woodsman's [Belt] I have some errands that need to be done.

**You say:** `armor`



>**Ellen Daleson says:** Oh you wish to get the armor that Alton's great granddaddy used to wear. If you are a ranger just let me know.

**You say:** `belt`



>**Ellen Daleson says:** If you want the Woodsman's Belt bring me a moon jewel, a mark of the environment, a gold pointer, and a broken ancient blade.

**You say:** `cape`



>**Ellen Daleson says:** If you want the Woodsman's Cape bring me a sky jewel, a mark of creatures, a wondrous stone, and a marble statuette.

**You say:** `choker`



>**Ellen Daleson says:** If you want the Woodsman's Choker bring me an astral jewel, a mark of ambidexterity, and a small ancient sculpture.

**You say:** `gauntlets`



>**Ellen Daleson says:** If you want the Woodsman's Guantlets bring me a meteor jewel, a mark of animals, and a tattered old card.

**You say:** `mantle`



>**Ellen Daleson says:** If you want the Woodsman's Mantle bring me a sun jewel, a mark of rivers, and a temporal sack.

**You say:** `mask`



>**Ellen Daleson says:** If you want the Woodsman's Mask bring me a cloud jewel, a mark of stone, and a platinum chain.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Broken Ancient Blade](/item/5850), [Gold Pointer](/item/5849), [Mark of the Environment](/item/5848), [Moon Jewel](/item/4489)) then 


FactionReward(e)


 **You receive:**  [Woodsman's Girdle](/item/3957) (+25000 exp)

elseif( **You turn in:** [Marble Statuette](/item/5844), [Mark of Creatures](/item/5698), [Sky Jewel](/item/4492), [Wondrous Stone](/item/5699)) then 


FactionReward(e)


 **You receive:**  [Woodsman's Cape](/item/3954) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Mark of Ambidexterity](/item/5981), [Small Ancient Sculpture](/item/5847)) then 


FactionReward(e)


 **You receive:**  [Woodsman's Gorget](/item/3956) (+25000 exp)

elseif( **You turn in:** [Mark of Animals](/item/5845), [Meteor Jewel](/item/4493), [Tattered Old Card](/item/5846)) then 


FactionReward(e)


 **You receive:**  [Woodsman's Gauntlets](/item/3955) (+25000 exp)

elseif( **You turn in:** [Mark of Rivers](/item/5690), [Sun Jewel](/item/4488), [Temporal Sack](/item/5691)) then 


FactionReward(e)


 **You receive:**  [Woodsman's Mantle](/item/3950) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Mark of Stone](/item/5696), [Platinum Chain](/item/5697)) then 


FactionReward(e)


 **You receive:**  [Woodsman's Mask](/item/3953) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Ellen Daleson says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)