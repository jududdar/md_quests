# Gunlok Jure
## Dialog

**You say:** `hail`



>**Gunlok Jure says:** Hail, Soandso!  Bow before the greatness of the Clerics of Underfoot!  It is good to be a paladin in such an order as ours - to fight the good fight and defend Kaladim from the evil and undead.  If you be a paladin, then I pray you find the [courage to battle the undead].

**You say:** `courage`



>**Gunlok Jure says:** Yes!!  To battle the undead is our greatest call.  There has been a rise in the number of dwarven skeletons seen in the Butcherblocks.  If you are a true member of this order, I shall reward you for the return of four bone chips.  We shall defend our land from evil!

**You say:** `remains`



if **Faction** >= Amiable then



>**Gunlok Jure says:** My brother Cromil ventured to the Plains of Karana on the continent of Antonica. He never returned. Rumor has it that his undead skeleton is now part of an undead army in the plains. Tothis curse, I ask all good paladins of this temple to return his bones to me. Nothing less than a spell is my reward for such a deed.


elseif( **Faction is** == Indifferent) then



>**Gunlok Jure says:** The Clerics of Underfoot have yet to see your faith directed towards our wills. Perhaps you should assist Master Gunlok Jure in the crusade against the undead.


else



>**Gunlok Jure says:** How dare you approach a member of the Clerics of Underfoot?!  Dogs such as you lie in the same bed as aviaks and ogres!

end

## Turn-Ins



if( **You turn in:** [Bone Chips](/item/13073), [Bone Chips](/item/13073), [Bone Chips](/item/13073), [Bone Chips](/item/13073)) then


>**Gunlok Jure says:** You have done well. We thank you for your deed with this humble reward. The power behind the raising of our dead shall soon be found. You will earn more respect with more bone chips. I only wish you could assist in the return of the [remains of Cromil].





* __Faction:__ [Clerics of Underfoot](/faction/227) (10)


 


* __Faction:__ [Kazon Stormhammer](/faction/274) (10)





* __Faction:__ [Miners Guild 249](/faction/293) (7)





 **You receive:** eq.ChooseRandom( [Small Tattered Skullcap](/item/2113), [Small Tattered Mask](/item/2114), [Small Tattered Gorget](/item/2115), [Small Patchwork Tunic](/item/2116), [Small Tattered Shoulderpads](/item/2117), [Small Patchwork Cloak](/item/2118), [Small Tattered Belt](/item/2119), [Small Patchwork Sleeves](/item/2120), [Small Tattered Wristbands](/item/2121), [Small Tattered Gloves](/item/2122), [Small Patchwork Pants](/item/2123), [Small Patchwork Boots](/item/2124), [Rusty Short Sword](/item/5013), [Rusty Axe](/item/5014), [Rusty Broad Sword](/item/5016), [Rusty Two Handed Sword](/item/5023), [Rusty Mace](/item/6011), [Torch](/item/13002), [Small Lantern](/item/13003)) (+1000 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Dwarf Bones](/item/13332)) then 


>**Gunlok Jure says:** Many thanks, my friend. Now my brother can rest in peace. Please take this spell. May it serve you well.





* __Faction:__ [Clerics of Underfoot](/faction/227) (20)


 


* __Faction:__ [Kazon Stormhammer](/faction/274) (20)





* __Faction:__ [Miners Guild 249](/faction/293) (15)





 **You receive:** eq.ChooseRandom( [Spell: Flash of Light](/item/15201), [Spell: Spook the Dead](/item/15209), [Spell: Hammer of Wrath](/item/15223), [Spell: Root](/item/15230)) (+10000 exp)

**This NPC *should* return incorrect items given.**
