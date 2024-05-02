# Brodlan Remdo
## Dialog

**You say:** `hail`



>**Brodlan Remdo says:** Why hello, I'm in charge of the fishing operations here on Jern's Isle.  [Fish] are my area of expertise.

**You say:** `fish`



>**Brodlan Remdo says:** We have fish come in here all the time. Sometimes we catch an [oddity] now and again.

**You say:** `oddity`



>**Brodlan Remdo says:** Once we pulled up this ancient chest filled with this [dark plate armor].

**You say:** `armor`



>**Brodlan Remdo says:** Looked the like kind of armor a dark knight would wear. if ya want it I'm sure we could arrange a [trade] of some sort.

**You say:** `trade`



>**Brodlan Remdo says:** Since Trevor and I are the ones that found it we split it between ourselves. I have a [helm], [breastplate], [vambraces], [greaves], [pauldrons], [bracer], and [boots]. Ask Trevor about the rest of the armor.

**You say:** `breastplate`



>**Brodlan Remdo says:** For the darkened knight's breastplate fetch me a cloud jewel. a mark of fear. a delicate glass sculpture. and a painted ornament.

**You say:** `vambraces`



>**Brodlan Remdo says:** For the darkened knight's vambraces fetch me a sky jewel. a mark of terror. a runed ornamental mace. and an ancient tablet.

**You say:** `greaves`



>**Brodlan Remdo says:** For the darkened knight's greaves fetch me a meteor jewel. a mark of dread. the King's Tome. and a polished ivory idol.

**You say:** `pauldrons`



>**Brodlan Remdo says:** For the darkened knight's pauldrons fetch me an astral jewel. a mark of hatred. and an ancient petrified tulip.

**You say:** `bracer`



>**Brodlan Remdo says:** For the darkened knight's bracer fetch me a sun jewel. a mark of intimidation. and a small rough marble figurine.

**You say:** `boots`



>**Brodlan Remdo says:** For the darkened knight's boots fetch me a moon jewel. a mark of horror. and a fanged talisman.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5871" data-url="5871" class="tooltip-link link">Mark of Horror</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/5872" data-url="5872" class="tooltip-link link">Fanged Talisman</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_545.png" alt="" /> <a
                                href="/item/3965" data-url="3965" class="tooltip-link link">Darkened Knight's Boots</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5869" data-url="5869" class="tooltip-link link">Mark of Intimidation</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/5870" data-url="5870" class="tooltip-link link">Small Rough Marble Figurine</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_671.png" alt="" /> <a
                                href="/item/3964" data-url="3964" class="tooltip-link link">Darkened Knight's Bracer</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5857" data-url="5857" class="tooltip-link link">Mark of Fear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/5860" data-url="5860" class="tooltip-link link">Delicate Glass Sculpture</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_619.png" alt="" /> <a
                                href="/item/5859" data-url="5859" class="tooltip-link link">Painted Ornament</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_624.png" alt="" /> <a
                                href="/item/3960" data-url="3960" class="tooltip-link link">Darkened Knight's Breastplate</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5864" data-url="5864" class="tooltip-link link">Mark of Dread</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/5865" data-url="5865" class="tooltip-link link">King's Tome</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/5866" data-url="5866" class="tooltip-link link">Polished Ivory Idol</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_611.png" alt="" /> <a
                                href="/item/3962" data-url="3962" class="tooltip-link link">Darkened Knight's Greaves</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5854" data-url="5854" class="tooltip-link link">Mark of Shadows</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/5855" data-url="5855" class="tooltip-link link">Primitive Totem</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_618.png" alt="" /> <a
                                href="/item/5856" data-url="5856" class="tooltip-link link">Golden Spoon</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/3959" data-url="3959" class="tooltip-link link">Darkened Knight's Helm</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5873" data-url="5873" class="tooltip-link link">Mark of Dark Fate</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/5874" data-url="5874" class="tooltip-link link">Crystalline Idol</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_772.png" alt="" /> <a
                                href="/item/3966" data-url="3966" class="tooltip-link link">Darkened Knight's Mask</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5867" data-url="5867" class="tooltip-link link">Mark of Hatred</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_721.png" alt="" /> <a
                                href="/item/5868" data-url="5868" class="tooltip-link link">Ancient Petrified Tulip</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_798.png" alt="" /> <a
                                href="/item/3963" data-url="3963" class="tooltip-link link">Darkened Knight's Pauldrons</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5861" data-url="5861" class="tooltip-link link">Mark of Terror</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/5862" data-url="5862" class="tooltip-link link">Runed Ornamental Mace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/5863" data-url="5863" class="tooltip-link link">Ancient Tablet</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_546.png" alt="" /> <a
                                href="/item/3961" data-url="3961" class="tooltip-link link">Darkened Knight's Vambraces</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Brodlan Remdo says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)