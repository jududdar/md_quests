# Vornol Transon



[Vornol Transon](/npc/170124) is a level 61 Erudite GM Magician that spawns in [Twilight](/zone/170).



## Dialog

**You say:** `hail`



>*Vornol Transon pauses for a second staring off into the distance. 'Ah welcome friend. I am Vornol, a summoner of sorts, and master of this tower.'*

**You say:** `magician`



>**Vornol Transon says:** Most excellent what I have is some armor, if you will do few errands for me it is yours. The pieces I have are the cap, robe, sleeves, pants, shawl, and bracer. My apprentice, the lady Galdara, has the rest. Just ask her about armor and she will tell you what you need to do.

**You say:** `cap`



>**Vornol Transon says:** For the cap you will have to bring back to me a sun jewel, a fire idol, a fire marked scroll and a runed ring of fire.

**You say:** `robe`



>**Vornol Transon says:** For the robe you will have to bring back to me a moon jewel, a vial of purified fire, a vial of purified water, and a vial of purified air.

**You say:** `sleeves`



>**Vornol Transon says:** For the sleeves you will have to bring back to me a star jewel, an air idol, an air marked scroll and a runed ring of air.

**You say:** `pants`



>**Vornol Transon says:** For the pants you will have to bring back to me a cloud jewel, an earth idol, an earth marked scroll, and a runed ring of earth.

**You say:** `shawl`



>**Vornol Transon says:** For the shawl you will have to bring back to me a sky jewel, a talisman of burning earth, and a vial of purified earth.

**You say:** `bracer`



>**Vornol Transon says:** For the bracer you will have to bring back to me a meteor jewel, talisman of moisture, and a vial of aqua waters.
end



## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_894.png" alt="" /> <a
                                href="/item/4495" data-url="4495" class="tooltip-link link">Fire Idol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/4496" data-url="4496" class="tooltip-link link">Fire Marked Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1061.png" alt="" /> <a
                                href="/item/4497" data-url="4497" class="tooltip-link link">Runed Ring of Fire</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_639.png" alt="" /> <a
                                href="/item/3684" data-url="3684" class="tooltip-link link">Cap of Matter</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1153.png" alt="" /> <a
                                href="/item/4498" data-url="4498" class="tooltip-link link">Vial of Purified Fire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1153.png" alt="" /> <a
                                href="/item/4499" data-url="4499" class="tooltip-link link">Vial of Purified Water</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1153.png" alt="" /> <a
                                href="/item/4506" data-url="4506" class="tooltip-link link">Vial of Purified Air</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_931.png" alt="" /> <a
                                href="/item/3685" data-url="3685" class="tooltip-link link">Robe of Matter</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/4507" data-url="4507" class="tooltip-link link">Air Idol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/4508" data-url="4508" class="tooltip-link link">Air Marked Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_873.png" alt="" /> <a
                                href="/item/4509" data-url="4509" class="tooltip-link link">Runed Ring of Air</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_670.png" alt="" /> <a
                                href="/item/3686" data-url="3686" class="tooltip-link link">Sleeves of Matter</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/4510" data-url="4510" class="tooltip-link link">Earth Idol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/4511" data-url="4511" class="tooltip-link link">Earth Marked Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_674.png" alt="" /> <a
                                href="/item/4512" data-url="4512" class="tooltip-link link">Runed Ring of Earth</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_631.png" alt="" /> <a
                                href="/item/3687" data-url="3687" class="tooltip-link link">Pants of Matter</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_754.png" alt="" /> <a
                                href="/item/4513" data-url="4513" class="tooltip-link link">Talisman of Burning Earth</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1153.png" alt="" /> <a
                                href="/item/4514" data-url="4514" class="tooltip-link link">Vial of Purified Earth</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_665.png" alt="" /> <a
                                href="/item/3688" data-url="3688" class="tooltip-link link">Shawl of Matter</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_754.png" alt="" /> <a
                                href="/item/4584" data-url="4584" class="tooltip-link link">Talisman of Moisture</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1160.png" alt="" /> <a
                                href="/item/4585" data-url="4585" class="tooltip-link link">Vial of Aqua Waters</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_638.png" alt="" /> <a
                                href="/item/3689" data-url="3689" class="tooltip-link link">Bracer of Matter</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Vornol Transon says:** Soandso take this and use it with pride.

Your faction standing with [Vornol Transon](/faction/1547) got better (<span class='text-success'>+5</span>)