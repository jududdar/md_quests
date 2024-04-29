# Herald Shelia Gransith
## Dialog

**You say:** `hail`



>**Herald Shelia Gransith says:** Welcome to the Twilight Sea!  This is the docking entrance to Katta Castellum. Soandso. Tell me do you know any songs?

**You say:** `songs`



>**Herald Shelia Gransith says:** Ah you do. You don't happen to be a bard do you?

**You say:** `bard`



>**Herald Shelia Gransith says:** Great. I have just what you need. Would you like to earn some armor?

**You say:** `armor`



>**Herald Shelia Gransith says:** I thought so I have a [helm], [breastplate], [vambraces], [greaves], [pauldrons], [bracer], and [boots]. For the rest speak to Brolan over there about armor.

**You say:** `breastplate`



>**Herald Shelia Gransith says:** For the breastplate you must bring me an astral jewel. a mark of music. a diamond studded medal. and a glorious flower.

**You say:** `vambraces`



>**Herald Shelia Gransith says:** For the vambraces you must bring me a sun jewel. a mark of entertainment. a sapphire studded medal. and velvet sleeves.

**You say:** `greaves`



>**Herald Shelia Gransith says:** For the greaves you must bring me a moon jewel. a mark of the drum. an emerald studded medal. and memory crystal.

**You say:** `pauldrons`



>**Herald Shelia Gransith says:** For the pauldrons you must bring me a star jewel. a mark of the mandolin. and an opal studded medal.

**You say:** `bracer`



>**Herald Shelia Gransith says:** For the bracer you must bring me a cloud jewel. a mark of song. and a pearl studded medal.

**You say:** `boots`



>**Herald Shelia Gransith says:** For the boots you must bring me a sky jewel. a mark of poetry. and a star ruby studded medal.

**You say:** `helm`



>**Herald Shelia Gransith says:** For the helm you must bring me a meteor jewel, a mark of rhythm, a ruby studded medal, and a fancy necklace.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Mark of Poetry](/item/5347), [Sky Jewel](/item/4492), [Star Ruby Studded Medal](/item/5348)) then


FactionReward(e)


 **You receive:**  [Bravado's Boots](/item/3909) (+25000 exp)

elseif( **You turn in:** [Pearl Studded Medal](/item/5346), [Mark of Song](/item/5345), [Cloud Jewel](/item/4491)) then


FactionReward(e)


 **You receive:**  [Bravado's Bracer](/item/3908) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Diamond Studded Medal](/item/5335), [Glorious Flower](/item/5336), [Mark of Music](/item/5334)) then


FactionReward(e)


 **You receive:**  [Bravado's Breastplate](/item/3898) (+25000 exp)

elseif( **You turn in:** [Emerald Studded Medal](/item/5341), [Mark of the Drum](/item/5340), [Memory Crystal](/item/5342), [Moon Jewel](/item/4489)) then


FactionReward(e)


 **You receive:**  [Bravado's Greaves](/item/3900) (+25000 exp)

elseif( **You turn in:** [Mark of the Mandolin](/item/5343), [Opal Studded Medal](/item/5344), [Star Jewel](/item/4490)) then


FactionReward(e)


 **You receive:**  [Bravado's Pauldrons](/item/3907) (+25000 exp)

elseif( **You turn in:** [Mark of Entertainment](/item/5337), [Sapphire Studded Medal](/item/5338), [Sun Jewel](/item/4488), [Velvet Sleeves](/item/5339)) then


FactionReward(e)


 **You receive:**  [Bravado's Vambraces](/item/3899) (+25000 exp)

elseif( **You turn in:** [Fancy Necklace](/item/5330), [Mark of Rhythm](/item/5328), [Meteor Jewel](/item/4493), [Ruby Studded Medal](/item/5329)) then


FactionReward(e)


 **You receive:**  [Bravado's Helm](/item/3897) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Herald Shelia Gransith says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)