# Legionnaire Kayn
## Dialog

**You say:** `hail`



>*Legionnaire Kayn stands still, on watch for danger.*

**You say:** `armor`



>**Legionnaire Kayn says:** You must have been speaking to Derron, a mightier cleric ye couldn't find. Except for Donal the Wise of course. So tell me are ye also a cleric like Derron?

**You say:** `cleric`



>**Legionnaire Kayn says:** Ah then you must want the mask, cloak, gauntlets, talisman, girdle, and hammer that I be holdin'.

**You say:** `cloak`



>**Legionnaire Kayn says:** To get the cloak you must bring me a sky jewel, a mark of credence, a light etched fire opal, and a polished stone statuette.

**You say:** `gauntlets`



>**Legionnaire Kayn says:** To get the gauntlets you must bring me a meteor jewel, a mark of piety, and a light etched opal.

**You say:** `girdle`



>**Legionnaire Kayn says:** To get the girdle you must bring me a sun jewel, a mark of grace, a light etched diamond, and a dark eyed iris.

**You say:** `hammer`



>**Legionnaire Kayn says:** To get the hammer you must bring me a moon jewel, a mark of salvation, a light etched emerald, and the writ of distance.

**You say:** `mask`



>**Legionnaire Kayn says:** To get the mask you must bring me a cloud jewel, a mark of hope, and a light etched star ruby.

**You say:** `talisman`



>**Legionnaire Kayn says:** To get the talisman you must bring me an astral jewel, a mark of affirmation, and a light etched peridot.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Sky Jewel](/item/4492), [Mark of Credence](/item/4850), [Light Etched Fire Opal](/item/4858), [Polished Stone Statuette](/item/4859)) then 


FactionReward(e)


 **You receive:**  [Cloak of the Holy Rite](/item/3744) (+25000 exp)

elseif( **You turn in:** [Meteor Jewel](/item/4493), [Mark of Piety](/item/4860), [Light Etched Opal](/item/4868)) then 


FactionReward(e)


 **You receive:**  [Gauntlets of the Holy Rite](/item/3745) (+25000 exp)

elseif( **You turn in:** [Sun Jewel](/item/4488), [Mark of Grace](/item/4878), [Light Etched Diamond](/item/4879), [Dark Eyed Iris](/item/4880)) then 


FactionReward(e)


 **You receive:**  [Girdle of the Holy Rite](/item/3747) (+25000 exp)

elseif( **You turn in:** [Moon Jewel](/item/4489), [Mark of Salvation](/item/4888), [Light Etched Emerald](/item/4889), [Writ of Distance](/item/4890)) then 


FactionReward(e)


 **You receive:**  [Grand Hammer of the Holy Rite](/item/3748) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Mark of Hope](/item/4848), [Lite Etched Star Ruby](/item/4849)) then 


FactionReward(e)


 **You receive:**  [Mask of the Holy Rite](/item/3743) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Mark of Affirmation](/item/4869), [Light Etched Peridot](/item/4870)) then 


FactionReward(e)


 **You receive:**  [Talisman of the Holy Rite](/item/3746) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Legionnaire Kayn says:** Soandso take this and use it with pride.

* __Faction:__ [Vornol Transon](/faction/1547) (5)