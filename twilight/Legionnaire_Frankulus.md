# Legionnaire Frankulus


## Dialog

**You say:** `hail`



>*Legionnaire Frankulus sighs and looks at you. 'Another traveler to our fair city of Katta Castellum, you be careful now.'*

**You say:** `armor`



>**Legionnaire Frankulus says:** Yes I am one of the keepers of the soldier's armor. The pieces I have are the helm, breastplate, vambraces, greaves, pauldrons, bracer, and boots. Eandalion keeps the other pieces just ask him about armor.

**You say:** `boots`



>**Legionnaire Frankulus says:** For the boots you will have to bring to me a cloud jewel, a mark of the martial, and a hope ruby.

**You say:** `bracer`



>**Legionnaire Frankulus says:** For the bracer you will have to bring to me a star jewel, a mark of the siege, and a blue egg.

**You say:** `breastplate`



>**Legionnaire Frankulus says:** For the breastplate you will have to bring to me a meteor jewel, a mark of war, a weathered yew wand, and some dew of dawn.

**You say:** `greaves`



>**Legionnaire Frankulus says:** For the greaves you will have to bring to me a sun jewel, a mark of archery, a golden torch, and a small meteor fragment.

**You say:** `helm`



>**Legionnaire Frankulus says:** For the helm you will have to bring to me a sky jewel, a mark of battle, some petrified toes, and a fire blossom.

**You say:** `pauldrons`



>**Legionnaire Frankulus says:** For the pauldrons you will have to bring to me a moon jewel, a mark of swordsmanship, and a water blossom.

**You say:** `vambraces`



>**Legionnaire Frankulus says:** For the vambraces you will have to bring to me an astral jewel, a mark of arms, a small sponge, and a scorched rock.
end



## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5496" data-url="5496" class="tooltip-link link">Mark of the Martial</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_964.png" alt="" /> <a
                                href="/item/5497" data-url="5497" class="tooltip-link link">Hope Ruby</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_545.png" alt="" /> <a
                                href="/item/3939" data-url="3939" class="tooltip-link link">Soldier's Boots</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5494" data-url="5494" class="tooltip-link link">Mark of the Siege</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_871.png" alt="" /> <a
                                href="/item/5495" data-url="5495" class="tooltip-link link">Blue Egg</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_671.png" alt="" /> <a
                                href="/item/3938" data-url="3938" class="tooltip-link link">Soldier's Bracer</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5483" data-url="5483" class="tooltip-link link">Mark of War</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_809.png" alt="" /> <a
                                href="/item/5484" data-url="5484" class="tooltip-link link">Weathered Yew Wand</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1153.png" alt="" /> <a
                                href="/item/5485" data-url="5485" class="tooltip-link link">Dew of Dawn</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_624.png" alt="" /> <a
                                href="/item/3934" data-url="3934" class="tooltip-link link">Soldier's Breastplate</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5489" data-url="5489" class="tooltip-link link">Mark of Archery</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_547.png" alt="" /> <a
                                href="/item/5490" data-url="5490" class="tooltip-link link">Golden Torch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1031.png" alt="" /> <a
                                href="/item/5491" data-url="5491" class="tooltip-link link">Small Meteor Fragment</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_611.png" alt="" /> <a
                                href="/item/3936" data-url="3936" class="tooltip-link link">Soldier's Greaves</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5480" data-url="5480" class="tooltip-link link">Mark of Battle</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1094.png" alt="" /> <a
                                href="/item/5481" data-url="5481" class="tooltip-link link">Petrified Toes</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_721.png" alt="" /> <a
                                href="/item/5482" data-url="5482" class="tooltip-link link">Fire Blossom</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_628.png" alt="" /> <a
                                href="/item/3933" data-url="3933" class="tooltip-link link">Soldier's Helm</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5492" data-url="5492" class="tooltip-link link">Mark of Swordsmanship</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_721.png" alt="" /> <a
                                href="/item/5493" data-url="5493" class="tooltip-link link">Water Blossom</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_798.png" alt="" /> <a
                                href="/item/3937" data-url="3937" class="tooltip-link link">Soldier's Pauldrons</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5486" data-url="5486" class="tooltip-link link">Mark of Arms</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_790.png" alt="" /> <a
                                href="/item/5487" data-url="5487" class="tooltip-link link">Small Sponge</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_767.png" alt="" /> <a
                                href="/item/5488" data-url="5488" class="tooltip-link link">Scorched Rock</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_546.png" alt="" /> <a
                                href="/item/3935" data-url="3935" class="tooltip-link link">Soldier's Vambraces</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Legionnaire Frankulus says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)