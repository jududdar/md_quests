# Tamben Prinon



[Tamben Prinon](/npc/170147) is a level 35 Barbarian Warrior that spawns in [Twilight](/zone/170).



## Dialog

**You say:** `hail`



>*Tamben Prinon looks over you examining you from head to toe. 'Ye have the look of an adventurer. I have a tale to tell if you would like to hear it.*

**You say:** `tale`



>**Tamben Prinon says:** Years ago I and Jilan were traveling around the far reaches of this land. One day we came upon an old vah shir who was injured in the mountains. He implored us to help him. Do you wish me to continue?

**You say:** `continue`



>**Tamben Prinon says:** As I was saying this old vah shir required assistance.  We bound his wounds and he asked us to take his armor and give it to a Beastlord worthy of wearing it.  Are you a worthy beastlord?

**You say:** `cap`



>**Tamben Prinon says:** For the cap you must prove your worth. Go gather up a sun jewel, a mark of feral spirits, an embedded copper figurine, and a frosted stone.

**You say:** `tunic`



>**Tamben Prinon says:** For the tunic you must prove your worth. Go gather up a moon jewel, a mark of animal spirits, a silver gilded bracelet, and an embedded mithril figurine.

**You say:** `sleeves`



>**Tamben Prinon says:** For the sleeves you must prove your worth. Go gather a star jewel, a mark of wild spirits, an embedded clay figurine, and a furrowed carving.

**You say:** `leggings`



>**Tamben Prinon says:** For the leggings you must prove your worth. Go gather a cloud jewel, a mark of natural spirits, an embedded stone figurine, and a blue moonstone.

**You say:** `mantle`



>**Tamben Prinon says:** For the mantle you must prove your worth. Go gather a sky jewel, a mark of wilderness, and an embedded platinum figurine.

**You say:** `bracer`



>**Tamben Prinon says:** For the bracer you must prove your worth. Go gather a meteor jewel, a mark of animal training, and an embedded brass figurine.

**You say:** `boots`



>**Tamben Prinon says:** For the boots you must prove your worth. Go gather an astral jewel, a mark of beast mastery, and an embedded gold figurine.
end



## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5921" data-url="5921" class="tooltip-link link">Mark of Feral Spirits</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_894.png" alt="" /> <a
                                href="/item/5927" data-url="5927" class="tooltip-link link">Embedded Copper Figurine</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/5928" data-url="5928" class="tooltip-link link">Frosted Stone</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/3985" data-url="3985" class="tooltip-link link">Feral Cap</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5929" data-url="5929" class="tooltip-link link">Mark of Animal Spirits</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_521.png" alt="" /> <a
                                href="/item/5922" data-url="5922" class="tooltip-link link">Silver Gilded Bracelet</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/5923" data-url="5923" class="tooltip-link link">Embedded Mithril Figurine</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/3986" data-url="3986" class="tooltip-link link">Feral Tunic</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/5925" data-url="5925" class="tooltip-link link">Embedded Clay Figurine</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5924" data-url="5924" class="tooltip-link link">Mark of Wild Spirits</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_894.png" alt="" /> <a
                                href="/item/5926" data-url="5926" class="tooltip-link link">Furrowed Carving</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/3987" data-url="3987" class="tooltip-link link">Feral Sleeves</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5930" data-url="5930" class="tooltip-link link">Mark of Natural Spirits</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/5931" data-url="5931" class="tooltip-link link">Embedded Stone Figurine</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/5932" data-url="5932" class="tooltip-link link">Blue Moonstone</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/3988" data-url="3988" class="tooltip-link link">Feral Leggings</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5933" data-url="5933" class="tooltip-link link">Mark of Wilderness</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/5934" data-url="5934" class="tooltip-link link">Embedded Platinum Figurine</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/3989" data-url="3989" class="tooltip-link link">Feral Mantle</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5935" data-url="5935" class="tooltip-link link">Mark of Animal Training</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_894.png" alt="" /> <a
                                href="/item/5936" data-url="5936" class="tooltip-link link">Embedded Brass Figurine</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/3990" data-url="3990" class="tooltip-link link">Feral Bracer</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5937" data-url="5937" class="tooltip-link link">Mark of Beast Mastery</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_893.png" alt="" /> <a
                                href="/item/5938" data-url="5938" class="tooltip-link link">Embedded Gold Figurine</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/3991" data-url="3991" class="tooltip-link link">Feral Boots</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Tamben Prinon says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)