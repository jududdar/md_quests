# Gazoon Noihzog
## Dialog

**You say:** `hail`



>*Gazoon Noihzog gasps in astonishment. 'Who do you think you are coming to my island?  I didn't invite you!*

**You say:** `island`



>**Gazoon Noihzog says:** It's my island and no one else's! This is where I hang out to blow stuff up, well that and they kicked me out of Katta.

**You say:** `blow stuff`



>**Gazoon Noihzog says:** Yeah that's what I usually do here.  Why so interested, are ya a fellow wizard?

**You say:** `wizard`



>**Gazoon Noihzog says:** Oh boy do I have something that you want. A nice set of wizardly armor that you can really waggle yer fingers in.

**You say:** `armor`



>**Gazoon Noihzog says:** It's not free that's for sure. If you want the armor I have the cap, robe, sleeves, pants, shawl, bracer and sandals. My buddy Trizpo has the rest you should go ask him about the armor.

**You say:** `bracer`



>**Gazoon Noihzog says:** For the bracer you'll have to fetch me a cloud jewel, a mark of potency, and book of applied magic.

**You say:** `cap`



>**Gazoon Noihzog says:** For the cap you'll have to fetch me a meteor jewel, some explosive dust, a mark of explosion, and a book of wizardry.

**You say:** `pants`



>**Gazoon Noihzog says:** For the pants you'll have to fetch me a moon jewel, a mark of energy, a gilded branch and some fiery sand.

**You say:** `robe`



>**Gazoon Noihzog says:** For the robe you'll have to fetch me an astral jewel, a mark of sorcery, a book of sorcery, and a globe of power.

**You say:** `sandals`



>**Gazoon Noihzog says:** For the sandals you'll have to fetch me a sky jewel, a mark of intensity, and a sun stained steel rod.

**You say:** `shawl`



>**Gazoon Noihzog says:** For the shawl you'll have to fetch me a star jewel, a mark of force, and some tro jeg toes.

**You say:** `sleeves`



>**Gazoon Noihzog says:** For the sleeves you'll have to fetch me a sun jewel, a mark of implosion, some grub worm guts, and a fiery heart.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Book of Applied Magic](/item/4724), [Cloud Jewel](/item/4491), [Mark of Potency](/item/4723)) then 


FactionReward(e)


 **You receive:**  [Bracer of Detonation](/item/3715) (+25000 exp)

elseif( **You turn in:** [Book of Wizardry](/item/4711), [Explosive Dust](/item/4709), [Mark of Explosion](/item/4710), [Meteor Jewel](/item/4493)) then 


FactionReward(e)


 **You receive:**  [Cap of Detonation](/item/3710) (+25000 exp)

elseif( **You turn in:** [Fiery Sand](/item/4720), [Gilded Branch](/item/4719), [Mark of Energy](/item/4718), [Moon Jewel](/item/4489)) then 


FactionReward(e)


 **You receive:**  [Pants of Detonation](/item/3713) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Book of Sorcery](/item/4713), [Globe of Power](/item/4714), [Mark of Sorcery](/item/4712)) then 


FactionReward(e)


 **You receive:**  [Robe of Detonation](/item/3711) (+25000 exp)

elseif( **You turn in:** [Mark of Intensity](/item/4725), [Sky Jewel](/item/4492), [Sun Stained Steel Rod](/item/4726)) then 


FactionReward(e)


 **You receive:**  [Sandals of Detonation](/item/3716) (+25000 exp)

elseif( **You turn in:** [Mark of Force](/item/4721), [Star Jewel](/item/4490), [Tro Jeg Toes](/item/4722)) then 


FactionReward(e)


 **You receive:**  [Shawl of Detonation](/item/3714) (+25000 exp)

elseif( **You turn in:** [Fiery Heart](/item/4717), [Grub Worm Guts](/item/4716), [Mark of Implosion](/item/4715), [Sun Jewel](/item/4488)) then 


FactionReward(e)


 **You receive:**  [Sleeves of Detonation](/item/3712) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Gazoon Noihzog says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)