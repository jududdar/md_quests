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



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5875" data-url="5875" class="tooltip-link link">Mark of Twisted Souls</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1082.png" alt="" /> <a
                                href="/item/5876" data-url="5876" class="tooltip-link link">Chilled Brazier</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/5877" data-url="5877" class="tooltip-link link">Gem of Blue Skies</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_663.png" alt="" /> <a
                                href="/item/3967" data-url="3967" class="tooltip-link link">Darkened Knight's Cloak</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5880" data-url="5880" class="tooltip-link link">Mark of Darkness</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1082.png" alt="" /> <a
                                href="/item/5881" data-url="5881" class="tooltip-link link">Rune Stone Brazier</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_626.png" alt="" /> <a
                                href="/item/3969" data-url="3969" class="tooltip-link link">Darkened Knight's Gorget</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5878" data-url="5878" class="tooltip-link link">Mark of Fright</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/5879" data-url="5879" class="tooltip-link link">True Silver Idol</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_531.png" alt="" /> <a
                                href="/item/3968" data-url="3968" class="tooltip-link link">Darkened Knight's Gauntlets</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5882" data-url="5882" class="tooltip-link link">Mark of Gloom</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_500.png" alt="" /> <a
                                href="/item/5883" data-url="5883" class="tooltip-link link">Gilded Beads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/5884" data-url="5884" class="tooltip-link link">Etched Tablet</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_549.png" alt="" /> <a
                                href="/item/3970" data-url="3970" class="tooltip-link link">Darkened Knight's Girdle</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5885" data-url="5885" class="tooltip-link link">Mark of Night</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_511.png" alt="" /> <a
                                href="/item/5886" data-url="5886" class="tooltip-link link">Beaded Circlet</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/5887" data-url="5887" class="tooltip-link link">Heating Stone</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/3971" data-url="3971" class="tooltip-link link">Darkened Knight's Mace</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Trevor Nalinson says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)

