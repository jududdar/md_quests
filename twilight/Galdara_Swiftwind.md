# Galdara Swiftwind



[Galdara Swiftwind](/npc/170129) is a level 40 High Elf Magician that spawns in [Twilight](/zone/170).



## Dialog

**You say:** `hail`



>**Galdara Swiftwind says:** Hi, I'm one of master Vornol's four apprentices. My specialty is with all things concerning the element of air.

**You say:** `armor`



>**Galdara Swiftwind says:** You must have spoken with master Vornol. He has me keeping this armor for him and various tasks for those to do who wish to wear it. Tell me are you a magician?

**You say:** `magician`



>**Galdara Swiftwind says:** Very good, the pieces that I have are the sandals, mask, cloak, gloves, choker, belt, and a staff.

**You say:** `sandals`



>**Galdara Swiftwind says:** For the sandals you must bring me an astral jewel, a talisman of wind, and a mark of aeration.

**You say:** `mask`



>**Galdara Swiftwind says:** For the mask you must bring me a sun jewel, a talisman of earth, and a sack of shadowed soil.

**You say:** `cloak`



>**Galdara Swiftwind says:** For the cloak you must bring me a moon jewel, a water idol, a water marked scroll, and a runed ring of water.

**You say:** `gloves`



>**Galdara Swiftwind says:** For the gloves you must bring me a star jewel, petrified bones, and a vial of dark earth.

**You say:** `choker`



>**Galdara Swiftwind says:** For the choker you must bring me a cloud jewel, fiery gourd, and a flaming candle.

**You say:** `belt`



>**Galdara Swiftwind says:** For the belt you must bring me a sky jewel, a vial of the morning mist, fastened links and a water etched wand.

**You say:** `staff`



>**Galdara Swiftwind says:** For the staff you must me a meteor jewel, a fire etched wand, an earth etched wand, and an air etched wand.
end



## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_754.png" alt="" /> <a
                                href="/item/4586" data-url="4586" class="tooltip-link link">Talisman of Wind</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4587" data-url="4587" class="tooltip-link link">Mark of Aeration</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_558.png" alt="" /> <a
                                href="/item/3690" data-url="3690" class="tooltip-link link">Sandals of Matter</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_754.png" alt="" /> <a
                                href="/item/4588" data-url="4588" class="tooltip-link link">Talisman of Earth</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/4589" data-url="4589" class="tooltip-link link">Sack of Shadowed Soil</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_677.png" alt="" /> <a
                                href="/item/3691" data-url="3691" class="tooltip-link link">Veil of Matter</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/4597" data-url="4597" class="tooltip-link link">Water Idol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/4598" data-url="4598" class="tooltip-link link">Water Marked Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_880.png" alt="" /> <a
                                href="/item/4599" data-url="4599" class="tooltip-link link">Runed Ring of Water</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_839.png" alt="" /> <a
                                href="/item/3692" data-url="3692" class="tooltip-link link">Cloak of Matter</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/4600" data-url="4600" class="tooltip-link link">Petrified Bones</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1154.png" alt="" /> <a
                                href="/item/4601" data-url="4601" class="tooltip-link link">Vial of Dark Earth</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_517.png" alt="" /> <a
                                href="/item/3693" data-url="3693" class="tooltip-link link">Gloves of Matter</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_923.png" alt="" /> <a
                                href="/item/4602" data-url="4602" class="tooltip-link link">Fiery Gourd</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1127.png" alt="" /> <a
                                href="/item/4603" data-url="4603" class="tooltip-link link">Flaming Candle</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1046.png" alt="" /> <a
                                href="/item/3694" data-url="3694" class="tooltip-link link">Choker of Matter</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1155.png" alt="" /> <a
                                href="/item/4604" data-url="4604" class="tooltip-link link">Vial of the Morning Mist</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1235.png" alt="" /> <a
                                href="/item/4828" data-url="4828" class="tooltip-link link">Fastened Links</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_809.png" alt="" /> <a
                                href="/item/4605" data-url="4605" class="tooltip-link link">Water Etched Wand</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_572.png" alt="" /> <a
                                href="/item/3695" data-url="3695" class="tooltip-link link">Belt of Matter</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_809.png" alt="" /> <a
                                href="/item/4672" data-url="4672" class="tooltip-link link">Fire Etched Wand</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_809.png" alt="" /> <a
                                href="/item/4674" data-url="4674" class="tooltip-link link">Earth Etched Wand</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_809.png" alt="" /> <a
                                href="/item/4673" data-url="4673" class="tooltip-link link">Air Etched Wand</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/3696" data-url="3696" class="tooltip-link link">Staff of Matter</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Galdara Swiftwind says:** Soandso take this and use it with pride.

Your faction standing with [Vornol Transon](/faction/1547) got better (<span class='text-success'>+5</span>)