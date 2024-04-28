# Bumle Reminjar
## Dialog

**You say:** `hail`



>**Bumle Reminjar says:** Welcome, Soandso. The Cathedral of Underfoot welcomes all good persons. May you find peace from the dangers of Butcherblock within these walls. The paladins of this holy place are very much aware of the evils outside Kaladim. The threat of goblins and [birdmen] has increased.

**You say:** `birdmen`



>**Bumle Reminjar says:** The birdmen I speak of are the aviak krags. These vile creatures have desecrated our land. They have dared to perch upon our great statue. The king has instructed all noble paladins in this order to [destroy the krag chicks].

**You say:** `chicks`



if **Faction** >= Amiable then



>**Bumle Reminjar says:** Yes. You are known to have aided our cause. You shall continue by returning any aviak chick talons to me. I will reward you for the return of no fewer than four at a time. Go, and serve the will of the king!


elseif **Faction** >= Indifferent then



>**Bumle Reminjar says:** The Clerics of Underfoot have yet to see your faith directed towards our wills. Perhaps you should assist Master Gunlok Jure in the crusade against the undead.


else



>**Bumle Reminjar says:** How dare you approach a member of the Clerics of Underfoot?!  Dogs such as you lie in the same bed as aviaks and ogres!


**You say:** `elders`



if **Faction** >= Kindly then 



>**Bumle Reminjar says:** The krag elders are the strongest of the aviaks. Their might has been well-documented by our order. Our high ranking paladins are ordered to slay the eagles. If you are with us, return four aviak talons to me and a fine reward shall be yours. Perhaps even our cathedral tailors and scribes may donate to your quest.


elseif **Faction** >= Indifferent then



>**Bumle Reminjar says:** The Clerics of Underfoot have yet to see your faith directed towards our wills. Perhaps you should assist Master Gunlok Jure in the crusade against the undead.


else



>**Bumle Reminjar says:** How dare you approach a member of the Clerics of Underfoot?!  Dogs such as you lie in the same bed as aviaks and ogres!

end

## Turn-Ins



local text = "I shall reward you for no less than four aviak chick talons.";

local text1 = "There is only a reward for the return of four aviak talons.";



if **Faction** >= Amiable and  **You turn in:** [Aviak Chick Talon](/item/12157), [Aviak Chick Talon](/item/12157), [Aviak Chick Talon](/item/12157), [Aviak Chick Talon](/item/12157)


>**Bumle Reminjar says:** You have done well. Your deeds shall be recorded within our journals. Here, then, is your reward. May you strive to serve us to the full extent of your powers. The [elders] must also die.





* __Faction:__ [Clerics of Underfoot](/faction/227) (5)


* __Faction:__ [Kazon Stormhammer](/faction/274) (5)


* __Faction:__ [Miners Guild 249](/faction/293) (3)


 **You receive:** eq.ChooseRandom( [Small Tattered Skullcap](/item/2113), [Small Tattered Mask](/item/2114), [Small Tattered Gorget](/item/2115), [Small Patchwork Tunic](/item/2116), [Small Tattered Shoulderpads](/item/2117), [Small Patchwork Cloak](/item/2118), [Small Tattered Belt](/item/2119), [Small Patchwork Sleeves](/item/2120), [Small Tattered Wristbands](/item/2121), [Small Tattered Gloves](/item/2122), [Small Patchwork Pants](/item/2123), [Small Patchwork Boots](/item/2124), [Tarnished Long Sword](/item/5045), [Cast-Iron Warhammer](/item/6041)) (+5000 exp)

elseif **Faction** >= Kindly and  **You turn in:** [Aviak Talon](/item/12158), [Aviak Talon](/item/12158), [Aviak Talon](/item/12158), [Aviak Talon](/item/12158)


>**Bumle Reminjar says:** Fine work! You shall be known for your great deeds. Take this and may it aid you in your defense of Kaladim. Hail King Kazon!





* __Faction:__ [Clerics of Underfoot](/faction/227) (10)


* __Faction:__ [Kazon Stormhammer](/faction/274) (10)


* __Faction:__ [Miners Guild 249](/faction/293) (7)


 **You receive:** eq.ChooseRandom( [Small Tattered Skullcap](/item/2113), [Small Tattered Mask](/item/2114), [Small Tattered Gorget](/item/2115), [Small Patchwork Tunic](/item/2116), [Small Tattered Shoulderpads](/item/2117), [Small Patchwork Cloak](/item/2118), [Small Tattered Belt](/item/2119), [Small Patchwork Sleeves](/item/2120), [Small Tattered Wristbands](/item/2121), [Small Tattered Gloves](/item/2122), [Small Patchwork Pants](/item/2123), [Small Patchwork Boots](/item/2124), [Cast-Iron Long Sword](/item/5082), [Cast-Iron Warhammer](/item/6041), [Cast-Iron Mace](/item/6042), [Cast-Iron Two Handed Hammer](/item/6046), [Cast-Iron Rapier](/item/7032)) (+10000 exp)

**This NPC *should* return incorrect items given.**
