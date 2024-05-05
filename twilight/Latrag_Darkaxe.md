# Latrag Darkaxe



[Latrag Darkaxe](/npc/170143) is a level 40 Dwarf Warrior that spawns in [Twilight](/zone/170).



## Dialog

**You say:** `hail`



>*Latrag Darkaxe lets out a resounding belch. 'Har there lad! Ye be sure 'nuff to tell em all that Brewmaster Latrag is retiring.'*

**You say:** `retiring`



>**Latrag Darkaxe says:** Ya got that right. I'm goin' to concentrate more on me devotion to Brell as a holy knight!

**You say:** `knight`



>**Latrag Darkaxe says:** I be a paladin of Brell thar Soandso. Might ye be a paladin yerself?

**You say:** `paladin`



>**Latrag Darkaxe says:** That's good. Ya know I have some armor ye might be interested in.

**You say:** `armor`



>**Latrag Darkaxe says:** Yar! I have me a helm, breastplate, vambraces, greaves, pauldrons, and a bracer. If ye want the rest talk to the mighty holy warrior Trallen over there about armor.

**You say:** `breastplate`



>**Latrag Darkaxe says:** For the breastplate ye gotta bring me a star jewel, a mark of courage, a white marble bowl, and a jagged reed.

**You say:** `vambrace`



>**Latrag Darkaxe says:** For the vambraces ye gotta bring me a cloud jewel, a mark of righteousness, a runed card, and a pristine ebony idol

**You say:** `greaves`



>**Latrag Darkaxe says:** For the greaves ye gotta bring me a sky jewel, a mark of bravery, a sunflower fruit, and a weathered bundle of wood

**You say:** `pauldrons`



>**Latrag Darkaxe says:** For the pauldrons ye gotta bring me a meteor jewel, a mark of daring, and a life gem.

**You say:** `bracer`



>**Latrag Darkaxe says:** For the bracer ye gotta bring me an astral jewel, a mark of reliance, and some blessed water

**You say:** `helm`



>**Latrag Darkaxe says:** For the helm ye gotta bring me a moon jewel, a mark of valor, a withered branch, and a pale pearl.
end



## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5902" data-url="5902" class="tooltip-link link">Mark of Reliance</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_584.png" alt="" /> <a
                                href="/item/5903" data-url="5903" class="tooltip-link link">Blessed Water</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_671.png" alt="" /> <a
                                href="/item/3977" data-url="3977" class="tooltip-link link">Blessed Knight's Bracer</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5891" data-url="5891" class="tooltip-link link">Mark of Courage</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_858.png" alt="" /> <a
                                href="/item/5892" data-url="5892" class="tooltip-link link">White Marble Bowl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/5893" data-url="5893" class="tooltip-link link">Jagged Reed</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_624.png" alt="" /> <a
                                href="/item/3973" data-url="3973" class="tooltip-link link">Blessed Knight's Breastplate</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5897" data-url="5897" class="tooltip-link link">Mark of Bravery</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1037.png" alt="" /> <a
                                href="/item/5898" data-url="5898" class="tooltip-link link">Sunflower Fruit</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_978.png" alt="" /> <a
                                href="/item/5899" data-url="5899" class="tooltip-link link">Weathered Bundle of Wood</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_611.png" alt="" /> <a
                                href="/item/3975" data-url="3975" class="tooltip-link link">Blessed Knight's Greaves</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5888" data-url="5888" class="tooltip-link link">Mark of Valor</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/5889" data-url="5889" class="tooltip-link link">Withered Branch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_953.png" alt="" /> <a
                                href="/item/5890" data-url="5890" class="tooltip-link link">Pale Pearl</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_628.png" alt="" /> <a
                                href="/item/3972" data-url="3972" class="tooltip-link link">Blessed Knight's Helm</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5900" data-url="5900" class="tooltip-link link">Mark of Daring</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_947.png" alt="" /> <a
                                href="/item/5901" data-url="5901" class="tooltip-link link">Life Gem</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_798.png" alt="" /> <a
                                href="/item/3976" data-url="3976" class="tooltip-link link">Blessed Knight's Pauldrons</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5894" data-url="5894" class="tooltip-link link">Mark of Righteousness</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_649.png" alt="" /> <a
                                href="/item/5895" data-url="5895" class="tooltip-link link">Runic Card</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/5896" data-url="5896" class="tooltip-link link">Pristine Ebony Idol</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_546.png" alt="" /> <a
                                href="/item/3974" data-url="3974" class="tooltip-link link">Blessed Knight's Vambraces</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Latrag Darkaxe says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)