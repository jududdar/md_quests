# Xavier Sendorn
## Dialog

**You say:** `hail`



>*Xavier Sendorn nods at Soandso. 'Hey there!*

**You say:** `armor`



>**Xavier Sendorn says:** Oh, you've decided you're going to help Lara out with her visions? If so, I can reward you with armor if you happen to be an enchanter.

**You say:** `enchanter`



>**Xavier Sendorn says:** I have the sandals, mask, cloak, gloves, choker, belt, and staff.

**You say:** `sandals`



>**Xavier Sendorn says:** For the sandals you must get for me a meteor jewel, a mark of refinement, and a hope onyx.

**You say:** `mask`



>**Xavier Sendorn says:** For the mask you must get for me an astral jewel, a mark of charm, and a hope pearl.

**You say:** `cloak`



>**Xavier Sendorn says:** For the cloak you must get for me a sun jewel, a mark of desire, a hope diamond, and a tarnished silver nugget.

**You say:** `gloves`



>**Xavier Sendorn says:** For the gloves you must get for me a moon jewel, a mark of intellect, and a tarnished gold nugget.

**You say:** `choker`



>**Xavier Sendorn says:** For the choker you must get for me a star jewel, a mark of thought, and a tarnished platinum nugget.

**You say:** `belt`



>**Xavier Sendorn says:** For the belt you must get for me a cloud jewel, a mark of reason, a tarnished electrum nugget, and a friendship bracelet.

**You say:** `staff`



>**Xavier Sendorn says:** For the staff you must get for me a sky jewel, a mark of mind, an enchanted bundle of wood, and a shadow crystal.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Meteor Jewel](/item/4493), [Mark of Refinement](/item/4691), [Hope Onyx](/item/4692)) then 


FactionReward(e)


 **You receive:**  [Sandals of Enrapturement](/item/3703) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Mark of Charm](/item/4693), [Hope Pearl](/item/4694)) then 


FactionReward(e)


 **You receive:**  [Veil of Enrapturement](/item/3704) (+25000 exp)

elseif( **You turn in:** [Sun Jewel](/item/4488), [Mark of Desire](/item/4695), [Hope Diamond](/item/4696), [Tarnished Silver Nugget](/item/4697)) then 


FactionReward(e)


 **You receive:**  [Cape of Enrapturement](/item/3705) (+25000 exp)

elseif( **You turn in:** [Moon Jewel](/item/4489), [Mark of Intellect](/item/4698), [Tarnished Gold Nugget](/item/4699)) then 


FactionReward(e)


 **You receive:**  [Gloves of Enrapturement](/item/3706) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Mark of Thought](/item/4701), [Tarnished Platinum Nugget](/item/4702)) then 


FactionReward(e)


 **You receive:**  [Choker of Enrapturement](/item/3707) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Mark of Reason](/item/4703), [Tarnished Electrum Nugget](/item/4704), [Bracelet of Friendship](/item/4705)) then 


FactionReward(e)


 **You receive:**  [Belt of Enrapturement](/item/3708) (+25000 exp)

elseif( **You turn in:** [Sky Jewel](/item/4492), [Mark of Mind](/item/4706), [Enchanted Bundle of Wood](/item/4707), [Shadowed Crystal](/item/4708)) then 


FactionReward(e)


 **You receive:**  [Staff of Enrapturement](/item/3709) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Xavier Sendorn says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)