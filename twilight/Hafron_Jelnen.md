# Hafron Jelnen
## Dialog

**You say:** `hail`



>**Hafron Jelnen says:** Hail and well met, friend.  I'm one of master Vornol's four apprentices.  I am being trained to be an expert on all things dealing with the element of fire.

**You say:** `armor`



>**Hafron Jelnen says:** This armor is indeed mighty if you wish to have it you must do some tasks for me. I have the coif, mail, vambraces, greaves, pauldrons, bracer, and boots. My sister, Sarah, has the rest just ask her about armor and she will help you.

**You say:** `boots`



>**Hafron Jelnen says:** To get the boots you must fetch for me a moon jewel, a mark of the seer, and a hewed augury stone.

**You say:** `bracer`



>**Hafron Jelnen says:** To get the bracer you must fetch for me a sun jewel, a mark of soul, and a spirit gem.

**You say:** `coif`



>**Hafron Jelnen says:** To get the coif you must fetch for me a star jewel, a mark of sight, an ancient sun fetish, and the tablet of spirits.

**You say:** `greaves`



>**Hafron Jelnen says:** To get the greaves you must fetch for me a meteor jewel, a mark of omens, a pouch of false gems, and an adorned cap

**You say:** `mail`



>**Hafron Jelnen says:** To get the mail you must fetch for me a cloud jewel, a mark of vision, a writ of safid, and some throwing bones.

**You say:** `pauldrons`



>**Hafron Jelnen says:** To get the pauldrons you must fetch for me a astral jewel, a mark of spirit, and Genalan's Chronicle.

**You say:** `vambraces`



>**Hafron Jelnen says:** To get the vambraces you must fetch for me a sky jewel, a mark of prophecy, a polished stone fetish, and a woven anklet.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Moon Jewel](/item/4489), [Mark of Seers](/item/4936), [Hewed Augury Stone](/item/4937)) then 


FactionReward(e)


 **You receive:**  [Augur's Boots](/item/3755) (+25000 exp)

elseif( **You turn in:** [Sun Jewel](/item/4488), [Mark of Souls](/item/4934), [Spirit Gem](/item/4935)) then 


FactionReward(e)


 **You receive:**  [Augur's Bracer](/item/3754) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Mark of Sight](/item/4898), [Ancient Sun Fetish](/item/4899), [Tablet of Spirits](/item/4900)) then 


FactionReward(e)


 **You receive:**  [Augur's Coif](/item/3749) (+25000 exp)

elseif( **You turn in:** [Meteor Jewel](/item/4493), [Mark of Omens](/item/4929), [Pouch of False Gems](/item/4930), [Adorned Cap](/item/4931)) then 


FactionReward(e)


 **You receive:**  [Augur's Greaves](/item/3752) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Mark of Vision](/item/4908), [Writ of Safid](/item/4909), [Throwing Bones](/item/4910)) then 


FactionReward(e)


 **You receive:**  [Augur's Mail](/item/3750) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Mark of Spirit](/item/4932), [Genalan's Chronicle](/item/4933)) then 


FactionReward(e)


 **You receive:**  [Augur's Mantle](/item/3753) (+25000 exp)

elseif( **You turn in:** [Sky Jewel](/item/4492), [Mark of Prophecy](/item/4918), [Polished Stone Fetish](/item/4927), [Woven Anklet](/item/4928)) then 


FactionReward(e)


 **You receive:**  [Augur's Vambraces](/item/3751) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Hafron Jelnen says:** Soandso take this and use it with pride.

* __Faction:__ [Vornol Transon](/faction/1547) (5)