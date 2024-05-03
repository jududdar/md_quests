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



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5254" data-url="5254" class="tooltip-link link">Mark of Discipline</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1234.png" alt="" /> <a
                                href="/item/5255" data-url="5255" class="tooltip-link link">Oiled Scales</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_677.png" alt="" /> <a
                                href="/item/3782" data-url="3782" class="tooltip-link link">Steel Threaded Veil</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5256" data-url="5256" class="tooltip-link link">Mark of Training</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_894.png" alt="" /> <a
                                href="/item/5257" data-url="5257" class="tooltip-link link">Scorched Idol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_950.png" alt="" /> <a
                                href="/item/5258" data-url="5258" class="tooltip-link link">Gem of Longevity</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_840.png" alt="" /> <a
                                href="/item/3783" data-url="3783" class="tooltip-link link">Steel Threaded Cloak</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5259" data-url="5259" class="tooltip-link link">Mark of Rank</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_954.png" alt="" /> <a
                                href="/item/5260" data-url="5260" class="tooltip-link link">Golden Gem</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_517.png" alt="" /> <a
                                href="/item/3784" data-url="3784" class="tooltip-link link">Steel Threaded Hand Wraps</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5261" data-url="5261" class="tooltip-link link">Mark of Aggression</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/5262" data-url="5262" class="tooltip-link link">Sun Fiend Bones</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_851.png" alt="" /> <a
                                href="/item/3785" data-url="3785" class="tooltip-link link">Steel Threaded Choker</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5263" data-url="5263" class="tooltip-link link">Mark of Defense</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/5264" data-url="5264" class="tooltip-link link">Protector Gem</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/5266" data-url="5266" class="tooltip-link link">Indigo Sapphire</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_572.png" alt="" /> <a
                                href="/item/3786" data-url="3786" class="tooltip-link link">Steel Threaded Belt</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5265" data-url="5265" class="tooltip-link link">Mark of the Dragon</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/5267" data-url="5267" class="tooltip-link link">Embedded Gravel Tablet</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1235.png" alt="" /> <a
                                href="/item/5268" data-url="5268" class="tooltip-link link">Gilded Wrist Chain</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/3787" data-url="3787" class="tooltip-link link">Steel Tipped Bo Stick</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Legionnaire Allise says:** Soandso take this and use it with pride.

Your faction standing with [Vornol Transon](/faction/1547) got better (<span class='text-success'>+5</span>)