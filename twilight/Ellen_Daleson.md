# Ellen Daleson



[Ellen Daleson](/npc/170138) is a level 40 Human Warrior that spawns in [Twilight](/zone/170).



## Dialog

**You say:** `hail`



>**Ellen Daleson says:** Oh hello there. I'm in charge of the docks here and wife to Alton.

**You say:** `alton`



>**Ellen Daleson says:** My husband is the owner of Jern's Rest. It's been his family for ages ever since his great grandaddy Jern built it.

**You say:** `ranger`



>**Ellen Daleson says:** Very well. If you want the Woodsman's [Mantle], Woodsman's [Mask], Woodsman's [Cape], Woodsman's [Guantlets], Woodsman's [Choker], or Woodsman's [Belt] I have some errands that need to be done.

**You say:** `armor`



>**Ellen Daleson says:** Oh you wish to get the armor that Alton's great granddaddy used to wear. If you are a ranger just let me know.

**You say:** `belt`



>**Ellen Daleson says:** If you want the Woodsman's Belt bring me a moon jewel, a mark of the environment, a gold pointer, and a broken ancient blade.

**You say:** `cape`



>**Ellen Daleson says:** If you want the Woodsman's Cape bring me a sky jewel, a mark of creatures, a wondrous stone, and a marble statuette.

**You say:** `choker`



>**Ellen Daleson says:** If you want the Woodsman's Choker bring me an astral jewel, a mark of ambidexterity, and a small ancient sculpture.

**You say:** `gauntlets`



>**Ellen Daleson says:** If you want the Woodsman's Guantlets bring me a meteor jewel, a mark of animals, and a tattered old card.

**You say:** `mantle`



>**Ellen Daleson says:** If you want the Woodsman's Mantle bring me a sun jewel, a mark of rivers, and a temporal sack.

**You say:** `mask`



>**Ellen Daleson says:** If you want the Woodsman's Mask bring me a cloud jewel, a mark of stone, and a platinum chain.
end



## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5850" data-url="5850" class="tooltip-link link">Broken Ancient Blade</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_822.png" alt="" /> <a
                                href="/item/5849" data-url="5849" class="tooltip-link link">Gold Pointer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5848" data-url="5848" class="tooltip-link link">Mark of the Environment</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_503.png" alt="" /> <a
                                href="/item/3957" data-url="3957" class="tooltip-link link">Woodsman's Girdle</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/5844" data-url="5844" class="tooltip-link link">Marble Statuette</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5698" data-url="5698" class="tooltip-link link">Mark of Creatures</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/5699" data-url="5699" class="tooltip-link link">Wondrous Stone</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_661.png" alt="" /> <a
                                href="/item/3954" data-url="3954" class="tooltip-link link">Woodsman's Cape</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5981" data-url="5981" class="tooltip-link link">Mark of Ambidexterity</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/5847" data-url="5847" class="tooltip-link link">Small Ancient Sculpture</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_627.png" alt="" /> <a
                                href="/item/3956" data-url="3956" class="tooltip-link link">Woodsman's Gorget</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5845" data-url="5845" class="tooltip-link link">Mark of Animals</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_648.png" alt="" /> <a
                                href="/item/5846" data-url="5846" class="tooltip-link link">Tattered Old Card</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_526.png" alt="" /> <a
                                href="/item/3955" data-url="3955" class="tooltip-link link">Woodsman's Gauntlets</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5690" data-url="5690" class="tooltip-link link">Mark of Rivers</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/5691" data-url="5691" class="tooltip-link link">Temporal Sack</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_769.png" alt="" /> <a
                                href="/item/3950" data-url="3950" class="tooltip-link link">Woodsman's Mantle</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5696" data-url="5696" class="tooltip-link link">Mark of Stone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1235.png" alt="" /> <a
                                href="/item/5697" data-url="5697" class="tooltip-link link">Platinum Chain</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_770.png" alt="" /> <a
                                href="/item/3953" data-url="3953" class="tooltip-link link">Woodsman's Mask</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Ellen Daleson says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)