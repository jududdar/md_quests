# Alton Daleson
## Dialog

**You say:** `hail`



>**Alton Daleson says:** Welcome to Jern's Rest!  I'm the owner and proprietor of this inn, it's been in my family for generations.  My great grandaddy, Jern, built it back when Katta Castellum was first being built.  If ya be wantin' of anything don't hesitate to ask.

**You say:** `armor`



>**Alton Daleson says:** His armor has also been in the family for generations, if ye be a [ranger] I don't have much use for it running this inn. I'll just need something in return for it.
  
**You say:** `ranger`



>**Alton Daleson says:** Excellent! If you are interested I have the Woodsman's [Helm], Woodsmand's [Mail], Woodsman's [Vambraces], Woodsman's [Greaves], Woodsman's [Bracer], Woodsman's [Boots], and the Woodsman's [Axe]. If youa re interested in the rest of his armor you'll have to ask my wife Ellen, she'll have some errands you can run for her.
  
**You say:** `axe`



>**Alton Daleson says:** If you want the Woodsman's Axe you will have to aquire these items: a sun jewel, a mark of the naturalist, some ancient pottery, and a fossilized skull.
  
**You say:** `boots`



>**Alton Daleson says:** If you want the Woodsman's Boots you will have to acquire these items: a star jewel, a mark of timber, and a gilded steel rod.
  
**You say:** `bracer`



>**Alton Daleson says:** If you want the Woodsman's Bracer you will have to acquire these items: a moon jewel, a mark of lakes, and some lightning dust.
  
**You say:** `greaves`



>**Alton Daleson says:** If you want the Woodsman's Greaves you will have to acquire these items: an astral jewel, a mark of oceans, a pouch of fire stones, and a cat skin pouch.
  
**You say:** `helm`



>**Alton Daleson says:** For the Woodsman's Helm you will have to acquire these items: a cloud jewel, a mark of leaves, a frost covered leaf, and some sea grass.
  
**You say:** `mail`



>**Alton Daleson says:** To get the Woodsman's Mail you will have to acquire these items: a sky jewel, a mark of forests, a frozen vial, and a tro jeg brain.
  
**You say:** `vambraces`



>**Alton Daleson says:** If you want the Woodsman's Vambraces you will have to acquire these items: a meteor jewel, a mark of mountains, a tro jeg eye, and a solstice rune.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_688.png" alt="" /> <a
                                href="/item/5852" data-url="5852" class="tooltip-link link">Ancient Pottery</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/5853" data-url="5853" class="tooltip-link link">Fossilized Skull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5851" data-url="5851" class="tooltip-link link">Mark of the Naturalist</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/3958" data-url="3958" class="tooltip-link link">Woodsman's Axe</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_732.png" alt="" /> <a
                                href="/item/5695" data-url="5695" class="tooltip-link link">Gilded Steel Rod</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5694" data-url="5694" class="tooltip-link link">Mark of Timber</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_779.png" alt="" /> <a
                                href="/item/3952" data-url="3952" class="tooltip-link link">Woodsman's Boots</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1074.png" alt="" /> <a
                                href="/item/5693" data-url="5693" class="tooltip-link link">Lightning Dust</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5692" data-url="5692" class="tooltip-link link">Mark of Lakes</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_620.png" alt="" /> <a
                                href="/item/3951" data-url="3951" class="tooltip-link link">Woodsman's Bracer</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_539.png" alt="" /> <a
                                href="/item/5689" data-url="5689" class="tooltip-link link">Cat Skin Pouch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5687" data-url="5687" class="tooltip-link link">Mark of Oceans</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/5688" data-url="5688" class="tooltip-link link">Pouch of Fire Stones</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_630.png" alt="" /> <a
                                href="/item/3949" data-url="3949" class="tooltip-link link">Woodsman's Greaves</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_795.png" alt="" /> <a
                                href="/item/5679" data-url="5679" class="tooltip-link link">Frost Covered Leaf</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5678" data-url="5678" class="tooltip-link link">Mark of Leaves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_795.png" alt="" /> <a
                                href="/item/5680" data-url="5680" class="tooltip-link link">Sea Grass</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_625.png" alt="" /> <a
                                href="/item/3946" data-url="3946" class="tooltip-link link">Woodsman's Coif</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1153.png" alt="" /> <a
                                href="/item/5682" data-url="5682" class="tooltip-link link">Frozen Vial</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5681" data-url="5681" class="tooltip-link link">Mark of Forests</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1204.png" alt="" /> <a
                                href="/item/5683" data-url="5683" class="tooltip-link link">Tro Jeg Brain</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_538.png" alt="" /> <a
                                href="/item/3947" data-url="3947" class="tooltip-link link">Woodsman's Mail</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5684" data-url="5684" class="tooltip-link link">Mark of Mountains</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5686" data-url="5686" class="tooltip-link link">Solstice Rune</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1130.png" alt="" /> <a
                                href="/item/5685" data-url="5685" class="tooltip-link link">Tro Jeg Eye</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_543.png" alt="" /> <a
                                href="/item/3948" data-url="3948" class="tooltip-link link">Woodsman's Vambraces</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Alton Daleson says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)
