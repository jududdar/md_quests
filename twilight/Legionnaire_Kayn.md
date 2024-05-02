# Legionnaire Kayn
## Dialog

**You say:** `hail`



>*Legionnaire Kayn stands still, on watch for danger.*

**You say:** `armor`



>**Legionnaire Kayn says:** You must have been speaking to Derron, a mightier cleric ye couldn't find. Except for Donal the Wise of course. So tell me are ye also a cleric like Derron?

**You say:** `cleric`



>**Legionnaire Kayn says:** Ah then you must want the mask, cloak, gauntlets, talisman, girdle, and hammer that I be holdin'.

**You say:** `cloak`



>**Legionnaire Kayn says:** To get the cloak you must bring me a sky jewel, a mark of credence, a light etched fire opal, and a polished stone statuette.

**You say:** `gauntlets`



>**Legionnaire Kayn says:** To get the gauntlets you must bring me a meteor jewel, a mark of piety, and a light etched opal.

**You say:** `girdle`



>**Legionnaire Kayn says:** To get the girdle you must bring me a sun jewel, a mark of grace, a light etched diamond, and a dark eyed iris.

**You say:** `hammer`



>**Legionnaire Kayn says:** To get the hammer you must bring me a moon jewel, a mark of salvation, a light etched emerald, and the writ of distance.

**You say:** `mask`



>**Legionnaire Kayn says:** To get the mask you must bring me a cloud jewel, a mark of hope, and a light etched star ruby.

**You say:** `talisman`



>**Legionnaire Kayn says:** To get the talisman you must bring me an astral jewel, a mark of affirmation, and a light etched peridot.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4850" data-url="4850" class="tooltip-link link">Mark of Credence</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_960.png" alt="" /> <a
                                href="/item/4858" data-url="4858" class="tooltip-link link">Light Etched Fire Opal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/4859" data-url="4859" class="tooltip-link link">Polished Stone Statuette</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_661.png" alt="" /> <a
                                href="/item/3744" data-url="3744" class="tooltip-link link">Cloak of the Holy Rite</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4860" data-url="4860" class="tooltip-link link">Mark of Piety</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_959.png" alt="" /> <a
                                href="/item/4868" data-url="4868" class="tooltip-link link">Light Etched Opal</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_531.png" alt="" /> <a
                                href="/item/3745" data-url="3745" class="tooltip-link link">Gauntlets of the Holy Rite</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4878" data-url="4878" class="tooltip-link link">Mark of Grace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/4879" data-url="4879" class="tooltip-link link">Light Etched Diamond</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_721.png" alt="" /> <a
                                href="/item/4880" data-url="4880" class="tooltip-link link">Dark Eyed Iris</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_549.png" alt="" /> <a
                                href="/item/3747" data-url="3747" class="tooltip-link link">Girdle of the Holy Rite</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4888" data-url="4888" class="tooltip-link link">Mark of Salvation</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_958.png" alt="" /> <a
                                href="/item/4889" data-url="4889" class="tooltip-link link">Light Etched Emerald</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/4890" data-url="4890" class="tooltip-link link">Writ of Distance</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/3748" data-url="3748" class="tooltip-link link">Grand Hammer of the Holy Rite</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4848" data-url="4848" class="tooltip-link link">Mark of Hope</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/4849" data-url="4849" class="tooltip-link link">Lite Etched Star Ruby</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_772.png" alt="" /> <a
                                href="/item/3743" data-url="3743" class="tooltip-link link">Mask of the Holy Rite</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4869" data-url="4869" class="tooltip-link link">Mark of Affirmation</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/4870" data-url="4870" class="tooltip-link link">Light Etched Peridot</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_566.png" alt="" /> <a
                                href="/item/3746" data-url="3746" class="tooltip-link link">Talisman of the Holy Rite</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Legionnaire Kayn says:** Soandso take this and use it with pride.

Your faction standing with [Vornol Transon](/faction/1547) got better (<span class='text-success'>+5</span>)