# Derron Gramjon
## Dialog

**You say:** `hail`



>*Derron Gramjon 's piercing eyes meets yours. 'Are ye a guest of Vornol's too? Have faith my friend but don't let that durn mage fool you, I know him better than anyone else. Well except for Valana of course.'*

**You say:** `cleric`



>**Derron Gramjon says:** I thought you might be. I have some armor to reward those that prove to be most holy.

**You say:** `armor`



>**Derron Gramjon says:** The armor I have is a helm, breastplate, vambraces, greaves, pauldrons, bracer, and boots. The rest you will have to get from my friend and guard Kayn. Just ask him about armor.

**You say:** `boots`



>**Derron Gramjon says:** For the boots you must prove yourself by bringing me a star jewel, a mark of belief and a light etched sapphire.

**You say:** `bracer`



>**Derron Gramjon says:** For the bracer you must prove yourself by bringing me a moon jewel, a mark of truth, and a light etched ruby.

**You say:** `breastplate`



>**Derron Gramjon says:** For the breastplate you must prove yourself by bringing me a sky jewel, a mark of faith, genuine leather padding, and a brazier of light.

**You say:** `greaves`



>**Derron Gramjon says:** For the greaves you must prove yourself by bringing me an astral jewel, a mark of purity, a lexicon of omens, and a candle of rites.

**You say:** `helm`



>**Derron Gramjon says:** For the helm you must prove yourself by bringing me a cloud jewel, a mark of remedy, a vial of holy water, and a holy statuette.

**You say:** `pauldrons`



>**Derron Gramjon says:** For the pauldrons you must prove yourself by bringing me a sun jewel, a mark of the divine, and decorative bracers of wistfulness.

**You say:** `vambraces`



>**Derron Gramjon says:** For the vambraces you must prove yourself by bringing me a meteor jewel, a mark of the holy, a tome of deities, and a restored tapestry.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Star Jewel](/item/4490), [Mark of Belief](/item/4839), [Light Etched of Sapphire](/item/4840)) then 


FactionReward(e)


 **You receive:**  [Boots of the Holy Rite](/item/3742) (+25000 exp)

elseif( **You turn in:** [Light Etched Ruby](/item/4838), [Mark of Truth](/item/4829), [Moon Jewel](/item/4489)) then 


FactionReward(e)


 **You receive:**  [Bracer of the Holy Rite](/item/3741) (+25000 exp)

elseif( **You turn in:** [Brazier of Light](/item/4798), [Genuine Leather Padding](/item/4797), [Mark of Faith](/item/4796), [Sky Jewel](/item/4492)) then 


FactionReward(e)


 **You receive:**  [Breastplate of the Holy Rite](/item/3737) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Candle of Rites](/item/4818), [Lexicon of Omens](/item/4810), [Mark of Purity](/item/4809)) then 


FactionReward(e)


 **You receive:**  [Greaves of the Holy Rite](/item/3739) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Holy Statuette](/item/4795), [Mark of Remedy](/item/4793), [Vial of Holy Water](/item/4794)) then 


FactionReward(e)


 **You receive:**  [Helm of the Holy Rite](/item/3736) (+25000 exp)

elseif( **You turn in:** [Decorative Bracers of Wistfulnees](/item/4820), [Mark of the Divine](/item/4819), [Sun Jewel](/item/4488)) then 


FactionReward(e)


 **You receive:**  [Pauldrons of the Holy Rite](/item/3740) (+25000 exp)

elseif( **You turn in:** [Mark of the Holy](/item/4799), [Meteor Jewel](/item/4493), [Restored Tapestry](/item/4808), [Tome of Deities](/item/4800)) then 


FactionReward(e)


 **You receive:**  [Vambraces of the Holy Rite](/item/3738) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Derron Gramjon says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)