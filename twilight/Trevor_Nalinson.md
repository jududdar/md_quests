# Trevor Nalinson
## Dialog

**You say:** `hail`



>**Trevor Nalinson says:** Can't ya see I'm busy working? Leave me be.

**You say:** `armor`



>**Trevor Nalinson says:** Bah, Brodlan should know better than opening his big mouth. Anyway this looks like armor for a dark knight if ye want to trade for it.

**You say:** `trade`



>**Trevor Nalinson says:** Good ya want to trade. I have the mask, cloak, gauntlets, gorget, girdle, and mace. Just tell me what piece you want to trade for and I'll tell ya what I want.

**You say:** `cloak`



>**Trevor Nalinson says:** For the darkened knight's cloak you'll have to bring me a cloud jewel, a mark of twisted souls, a chilled brazier, and a gem of blue skies.

**You say:** `gauntlets`



>**Trevor Nalinson says:** For the darkened knight's gauntlets you'll have bring me a sky jewel, a mark of fright, and a true silver idol

**You say:** `girdle`



>**Trevor Nalinson says:** For the darkened knight's girdle you'll have to bring me an astral jewel, a mark of gloom, some gilded beads, and an etched tablet.

**You say:** `girdle`



>**Trevor Nalinson says:** For the darkened knigh's gorget you'll have to bring me a meteor jewel, a mark of darkness, a runed stone brazier.

**You say:** `mace`



>**Trevor Nalinson says:** For the darkened knight's mace you'll have to bring me a sun jewel, a mark of night, a beaded circlet, and a heating stone.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Cloud Jewel](/item/4491), [Mark of Twisted Souls](/item/5875), [Chilled Brazier](/item/5876), [Gem of Blue Skies](/item/5877)) then 


FactionReward(e)


 **You receive:**  [Darkened Knight's Cloak](/item/3967) (+25000 exp)

elseif( **You turn in:** [Meteor Jewel](/item/4493), [Mark of Darkness](/item/5880), [Rune Stone Brazier](/item/5881)) then 


FactionReward(e)


 **You receive:**  [Darkened Knight's Gorget](/item/3969) (+25000 exp)

elseif( **You turn in:** [Sky Jewel](/item/4492), [Mark of Fright](/item/5878), [True Silver Idol](/item/5879)) then 


FactionReward(e)


 **You receive:**  [Darkened Knight's Gauntlets](/item/3968) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Mark of Gloom](/item/5882), [Gilded Beads](/item/5883), [Etched Tablet](/item/5884)) then 


FactionReward(e)


 **You receive:**  [Darkened Knight's Girdle](/item/3970) (+25000 exp)

elseif( **You turn in:** [Sun Jewel](/item/4488), [Mark of Night](/item/5885), [Beaded Circlet](/item/5886), [Heating Stone](/item/5887)) then 


FactionReward(e)


 **You receive:**  [Darkened Knight's Mace](/item/3971) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Trevor Nalinson says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)

