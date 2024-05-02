# Derron Gramjon
## Dialog

**You say:** `hail`



>*Derron Gramjon 's piercing eyes meets yours. 'Are ye a guest of Vornol's too? Have faith my friend but don't let that durn mage fool you, I know him better than anyone else. Well except for Valana of course.'*

**You say:** `cleric`



>**Derron Gramjon says:** I thought you might be. I have some armor to reward those that prove to be most holy.

**You say:** `armor`



>**Derron Gramjon says:** The armor I have is a helm, breastplate, vambraces, greaves, pauldrons, bracer, and boots. The rest you will have to get from my friend and guard Kayn. Just ask him about armor.

**You say:** `boots`



>**Derron Gramjon says:** For the boots you must prove yourself by bringing me a star jewel, a mark of belief and a light etched sapphire.

**You say:** `bracer`



>**Derron Gramjon says:** For the bracer you must prove yourself by bringing me a moon jewel, a mark of truth, and a light etched ruby.

**You say:** `breastplate`



>**Derron Gramjon says:** For the breastplate you must prove yourself by bringing me a sky jewel, a mark of faith, genuine leather padding, and a brazier of light.

**You say:** `greaves`



>**Derron Gramjon says:** For the greaves you must prove yourself by bringing me an astral jewel, a mark of purity, a lexicon of omens, and a candle of rites.

**You say:** `helm`



>**Derron Gramjon says:** For the helm you must prove yourself by bringing me a cloud jewel, a mark of remedy, a vial of holy water, and a holy statuette.

**You say:** `pauldrons`



>**Derron Gramjon says:** For the pauldrons you must prove yourself by bringing me a sun jewel, a mark of the divine, and decorative bracers of wistfulness.

**You say:** `vambraces`



>**Derron Gramjon says:** For the vambraces you must prove yourself by bringing me a meteor jewel, a mark of the holy, a tome of deities, and a restored tapestry.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4839" data-url="4839" class="tooltip-link link">Mark of Belief</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/4840" data-url="4840" class="tooltip-link link">Light Etched of Sapphire</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_545.png" alt="" /> <a
                                href="/item/3742" data-url="3742" class="tooltip-link link">Boots of the Holy Rite</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_964.png" alt="" /> <a
                                href="/item/4838" data-url="4838" class="tooltip-link link">Light Etched Ruby</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4829" data-url="4829" class="tooltip-link link">Mark of Truth</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_671.png" alt="" /> <a
                                href="/item/3741" data-url="3741" class="tooltip-link link">Bracer of the Holy Rite</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1082.png" alt="" /> <a
                                href="/item/4798" data-url="4798" class="tooltip-link link">Brazier of Light</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/4797" data-url="4797" class="tooltip-link link">Genuine Leather Padding</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4796" data-url="4796" class="tooltip-link link">Mark of Faith</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_624.png" alt="" /> <a
                                href="/item/3737" data-url="3737" class="tooltip-link link">Breastplate of the Holy Rite</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1128.png" alt="" /> <a
                                href="/item/4818" data-url="4818" class="tooltip-link link">Candle of Rites</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/4810" data-url="4810" class="tooltip-link link">Lexicon of Omens</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4809" data-url="4809" class="tooltip-link link">Mark of Purity</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_540.png" alt="" /> <a
                                href="/item/3739" data-url="3739" class="tooltip-link link">Greaves of the Holy Rite</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/4795" data-url="4795" class="tooltip-link link">Holy Statuette</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4793" data-url="4793" class="tooltip-link link">Mark of Remedy</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1155.png" alt="" /> <a
                                href="/item/4794" data-url="4794" class="tooltip-link link">Vial of Holy Water</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_628.png" alt="" /> <a
                                href="/item/3736" data-url="3736" class="tooltip-link link">Helm of the Holy Rite</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/4820" data-url="4820" class="tooltip-link link">Decorative Bracers of Wistfulnees</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4819" data-url="4819" class="tooltip-link link">Mark of the Divine</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_798.png" alt="" /> <a
                                href="/item/3740" data-url="3740" class="tooltip-link link">Pauldrons of the Holy Rite</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4799" data-url="4799" class="tooltip-link link">Mark of the Holy</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_653.png" alt="" /> <a
                                href="/item/4808" data-url="4808" class="tooltip-link link">Restored Tapestry</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/4800" data-url="4800" class="tooltip-link link">Tome of Deities</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_546.png" alt="" /> <a
                                href="/item/3738" data-url="3738" class="tooltip-link link">Vambraces of the Holy Rite</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Derron Gramjon says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)