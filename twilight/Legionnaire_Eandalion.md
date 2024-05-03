# Legionnaire Eandalion


## Dialog

**You say:** `hail`



>**Legionnaire Eandalion says:** Salutations to you and your own. On your way to Katta are ya?

**You say:** `armor`



>**Legionnaire Eandalion says:** Frank must have told ya about the soldier's armor that we both keep to give to those worthy of wearing it. I have the mask, cloak, gauntlets, gorget, girdle, and swords.

**You say:** `cloak`



>**Legionnaire Eandalion says:** To get the cloak you will need to get me a meteor jewel, a mark of glory, a ring of wit, and some twilight fish scales.

**You say:** `gauntlets`



>**Legionnaire Eandalion says:** To get the gauntlets you will need to get me an astral jewel, a mark of opposition, and a hope quartz.

**You say:** `girdle`



>**Legionnaire Eandalion says:** To get the girdle you will need to get me a moon jewel, a mark of contention, a fire scorched stick, and a hope star ruby.

**You say:** `gorget`



>**Legionnaire Eandalion says:** To get the gorget you will need to get me a sun jewel, a mark of pride, and some star dust.

**You say:** `mask`



>**Legionnaire Eandalion says:** To get the mask you will need to get me a sky jewel, a mark of defiance, and a bag of scarlet sand.

**You say:** `sword`



>**Legionnaire Eandalion says:** To get the sword you will need to get me a star jewel, a mark of warfare, a hope fire opal, and some fire powder.
end



## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5530" data-url="5530" class="tooltip-link link">Mark of Glory</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_613.png" alt="" /> <a
                                href="/item/5584" data-url="5584" class="tooltip-link link">Ring of Wit</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_799.png" alt="" /> <a
                                href="/item/5585" data-url="5585" class="tooltip-link link">Twilight Fish Scales</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_663.png" alt="" /> <a
                                href="/item/3941" data-url="3941" class="tooltip-link link">Soldier's Cloak</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5586" data-url="5586" class="tooltip-link link">Mark of Opposition</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/5587" data-url="5587" class="tooltip-link link">Hope Quartz</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_531.png" alt="" /> <a
                                href="/item/3942" data-url="3942" class="tooltip-link link">Soldier's Gauntlets</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5590" data-url="5590" class="tooltip-link link">Mark of Contention</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/5591" data-url="5591" class="tooltip-link link">Fire Scorched Stick</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/5592" data-url="5592" class="tooltip-link link">Hope Star Ruby</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_549.png" alt="" /> <a
                                href="/item/3944" data-url="3944" class="tooltip-link link">Soldier's Girdle</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5588" data-url="5588" class="tooltip-link link">Mark of Pride</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1074.png" alt="" /> <a
                                href="/item/5589" data-url="5589" class="tooltip-link link">Star Dust</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_626.png" alt="" /> <a
                                href="/item/3943" data-url="3943" class="tooltip-link link">Soldier's Gorget</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5528" data-url="5528" class="tooltip-link link">Mark of Defiance</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/5529" data-url="5529" class="tooltip-link link">Bag of Scarlet Sand</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_772.png" alt="" /> <a
                                href="/item/3940" data-url="3940" class="tooltip-link link">Soldier's Mask</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5668" data-url="5668" class="tooltip-link link">Mark of Warfare</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_960.png" alt="" /> <a
                                href="/item/5669" data-url="5669" class="tooltip-link link">Hope Fire Opal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1076.png" alt="" /> <a
                                href="/item/5677" data-url="5677" class="tooltip-link link">Fire Powder</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/3945" data-url="3945" class="tooltip-link link">Soldier's Long Sword</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Legionnaire Eandalion says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)