# Brolan Geppal
## Dialog

**You say:** `hail`



>**Brolan Geppal says:** Well met friend, lovely day isn't it?

**You say:** `armor`



>**Brolan Geppal says:** Yes Shelia told me I may have some people asking me about the armor I have. Are ya a bard?

**You say:** `bard`



>**Brolan Geppal says:** Good, I have a [mask], [cloak], [gauntlets], [gorget], [girdle], and a [sword].

**You say:** `cloak`



>**Brolan Geppal says:** For the cloak you must gather these things. An Astral jewel, a mark of melody, an onyx studded medal, and a porous rock.

**You say:** `gauntlets`



>**Brolan Geppal says:** For the gauntlets you must gather these things. A sun jewel, a mark of anthems, and a fire emerald studded medal.

**You say:** `girdle`



>**Brolan Geppal says:** For the girdle you must gather these things. A star jewel, a mark of composition, a peridot studded medal, and a seared brand.

**You say:** `gorget`



>**Brolan Geppal says:** For the gorget you must gather these things a moon jewel, a mark of psalms, and a black pearl studded medal.

**You say:** `mask`



>**Brolan Geppal says:** For the mask you must gather these things a meteor jewel, a mark of tenor, and a star sapphire studded medal.

**You say:** `sword`



>**Brolan Geppal says:** For the sword you must gather these things a cloud jewel, a mark of chants, a red stone idol, and a moonstone studded medal.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if **You turn in:** [Astral Jewel](/item/4494), [Mark of Melody](/item/5393), [Onyx Studded Medal](/item/5394), [Porous Rock](/item/5395)


FactionReward(e)


 **You receive:**  [Bravado's Cape](/item/3928) (+25000 exp)

elseif **You turn in:** [Fire Emerald Studded Medal](/item/5397), [Mark of Anthems](/item/5396), [Sun Jewel](/item/4488)


FactionReward(e)


 **You receive:**  [Bravado's Gauntlets](/item/3929) (+25000 exp)
  
elseif **You turn in:** [Mark of Composition](/item/5474), [Peridot Studded Medal](/item/5475), [Seared Brand](/item/5476), [Star Jewel](/item/4490)


FactionReward(e)


 **You receive:**  [Bravado's Girdle](/item/3931) (+25000 exp)

elseif **You turn in:** [Black Pearl Studded Medal](/item/5399), [Mark of Psalms](/item/5398), [Moon Jewel](/item/4489)


FactionReward(e)


 **You receive:**  [Bravado's Gorget](/item/3930) (+25000 exp)

elseif **You turn in:** [Mark of Tenor](/item/5349), [Meteor Jewel](/item/4493), [Star Sapphire Studded Medal](/item/5354)


FactionReward(e)


 **You receive:**  [Bravado's Mask](/item/3910) (+25000 exp)

elseif **You turn in:** [Cloud Jewel](/item/4491), [Mark of Chants](/item/5477), [Moonstone Studded Medal](/item/5479), [Red Stone Idol](/item/5478)


FactionReward(e)


 **You receive:**  [Bravado's Blade](/item/3932) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Brolan Geppal says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)