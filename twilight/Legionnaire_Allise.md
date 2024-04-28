# Legionnaire Allise
## Dialog

**You say:** `hail`



>*Legionnaire Allise stands stoutly at her post.*

**You say:** `armor`



>*Legionnaire Allise smiles at Soandso. 'Valana must have sent you here. Tell me, are you a monk?'*

**You say:** `monk`



>**Legionnaire Allise says:** Good the pieces I have are the veil, cloak, hand wraps, choker, belt, and a bo stick.

**You say:** `veil`



>**Legionnaire Allise says:** To receive the veil you must retrieve for me a sun jewel, a mark of discipline, and some oiled scales.

**You say:** `cloak`



>**Legionnaire Allise says:** To receive the cloak you must retrieve for me a moon jewel, a mark of training, a scorched idol, and a gem of longevity.

**You say:** `hand wraps`



>**Legionnaire Allise says:** To receive the hand wraps you must retrieve for me a star jewel, a mark of rank, and a golden gem.

**You say:** `choker`



>**Legionnaire Allise says:** To receive the choker you must retrieve for me a cloud jewel, a mark of aggression, and some sun fiend bones.

**You say:** `belt`



>**Legionnaire Allise says:** To receive the belt you must retrieve for me a sky jewel, a mark of defense, a protector gem, and an indigo sapphire.

**You say:** `bo stick`



>**Legionnaire Allise says:** To receive the bo stick you must retrieve for me a meteor jewel, a mark of the dragon, an embedded gravel tablet, and a gilded wrist chain.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if **You turn in:** [Sun Jewel](/item/4488), [Mark of Discipline](/item/5254), [Oiled Scales](/item/5255)


FactionReward(e)


 **You receive:**  [Steel Threaded Veil](/item/3782) (+25000 exp)

elseif **You turn in:** [Moon Jewel](/item/4489), [Mark of Training](/item/5256), [Scorched Idol](/item/5257), [Gem of Longevity](/item/5258)


FactionReward(e)


 **You receive:**  [Steel Threaded Cloak](/item/3783) (+25000 exp)

elseif **You turn in:** [Star Jewel](/item/4490), [Mark of Rank](/item/5259), [Golden Gem](/item/5260)


FactionReward(e)


 **You receive:**  [Steel Threaded Hand Wraps](/item/3784) (+25000 exp)

elseif **You turn in:** [Cloud Jewel](/item/4491), [Mark of Aggression](/item/5261), [Sun Fiend Bones](/item/5262)


FactionReward(e)


 **You receive:**  [Steel Threaded Choker](/item/3785) (+25000 exp)

elseif **You turn in:** [Sky Jewel](/item/4492), [Mark of Defense](/item/5263), [Protector Gem](/item/5264), [Indigo Sapphire](/item/5266)


FactionReward(e)


 **You receive:**  [Steel Threaded Belt](/item/3786) (+25000 exp)

elseif **You turn in:** [Meteor Jewel](/item/4493), [Mark of the Dragon](/item/5265), [Embedded Gravel Tablet](/item/5267), [Gilded Wrist Chain](/item/5268)


FactionReward(e)


 **You receive:**  [Steel Tipped Bo Stick](/item/3787) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Legionnaire Allise says:** Soandso take this and use it with pride.

* __Faction:__ [Vornol Transon](/faction/1547) (5)