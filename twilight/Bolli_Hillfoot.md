# Bolli Hillfoot
## Dialog

**You say:** `hail`



>*Bolli Hillfoot looks at Soandso and smirks. 'I be Bolli and it's sure an honor to meet such a fine person such as yourself! I have plenty of deals for any stealthy types'*

**You say:** `deal`



>**Bolli Hillfoot says:** Ah, Soandso, you fancy yerself to be a rogue.  Well I can cut ya a deal on some armor if you be wantin' some.

**You say:** `armor`



>*Bolli Hillfoot smiles widely. 'Ah excellent, I have a coif, tunic, vambraces, greaves, mantle, bracer, and boots just ask about each one and Ill tell ya just what I want in return. Youll have to talk to my partner Liteema if you want the rest of the armor.'*

**You say:** `boots`



>**Bolli Hillfoot says:** If you want the Boots of Concealment go gather for me a meteor jewel, a mark of silence, and an engraved fire emerald statuette.

**You say:** `bracer`



>**Bolli Hillfoot says:** If you want the Bracer of Concealment go gather for me a sky jewel, a mark of cunning, and an engraved black diamond statuette.

**You say:** `tunic`



>**Bolli Hillfoot says:** If you want the Tunic of Concealment go gather for me a sun jewel, a mark of stealth, an engraved diamond statuette, and a tethered leash.

**You say:** `greaves`



>**Bolli Hillfoot says:** If you want the Greaves of Concealment go gather for me a star jewel, a mark of burglary, an engraved ruby statuette, and a small brass figurine.

**You say:** `coif`



>**Bolli Hillfoot says:** If you want the Coif of Concealment go gather for me an astral jewel, a mark of thievery, an engraved sapphire statuette, and a brass linked chain.

**You say:** `mantle`



>**Bolli Hillfoot says:** If you want the Mantle of Concealment go gather for me a cloud jewel, a mark of forgery, and an engraved star sapphire statuette.

**You say:** `vambraces`



>**Bolli Hillfoot says:** If you want the Vambraces of Concealment go gather for me a moon jewel, a mark of robbery, an engraved emerald statuette, and a half melted blade.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if **You turn in:** [Meteor Jewel](/item/4493), [Mark of Silence](/item/5285), [Engraved Fire Emerald Statuette](/item/5286)


FactionReward(e)


 **You receive:**  [Boots of Concealment](/item/3794) (+25000 exp)

elseif **You turn in:** [Sky Jewel](/item/4492), [Mark of Cunning](/item/5283), [Engraved Black Diamond Statuette](/item/5284)


FactionReward(e)


 **You receive:**  [Bracer of Concealment](/item/3793) (+25000 exp)

elseif **You turn in:** [Sun Jewel](/item/4488), [Mark of Stealth](/item/5296), [Engraved Diamond Statuette](/item/5273), [Tethered Leash](/item/5274)


FactionReward(e)


 **You receive:**  [Mail of Concealment](/item/3789) (+25000 exp)

elseif **You turn in:** [Star Jewel](/item/4490), [Mark of Burglary](/item/5278), [Engraved Ruby Statuette](/item/5279), [Small Brass Figurine](/item/5280)


FactionReward(e)


 **You receive:**  [Greaves of Concealment](/item/3791) (+25000 exp)

elseif **You turn in:** [Astral Jewel](/item/4494), [Mark of Thievery](/item/5269), [Engraved Sapphire Statuette](/item/5270), [Brass Linked Chain](/item/5271)


FactionReward(e)


 **You receive:**  [Coif of Concealment](/item/3788) (+25000 exp)

elseif **You turn in:** [Cloud Jewel](/item/4491), [Mark of Forgery](/item/5281), [Engraved Star Sapphire Statuette](/item/5282)


FactionReward(e)


 **You receive:**  [Mantle of Concealment](/item/3792) (+25000 exp)

elseif **You turn in:** [Moon Jewel](/item/4489), [Mark of Robbery](/item/5275), [Engraved Emerald Statuette](/item/5276), [Half Melted Blade](/item/5277)


FactionReward(e)


 **You receive:**  [Vambraces of Concealment](/item/3790) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Bolli Hillfoot says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)