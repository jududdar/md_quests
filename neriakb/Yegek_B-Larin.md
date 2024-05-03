# Yegek B-Larin


## Dialog

**You say:** `hail`



>**Yegek B-Larin says:** Welcome. A brother of the Indigo you must be. Why else would one dare to roam the corridors of the Cauldron of Hate? You were most likely sent to speak with Yegek. If so. speak up and tell Yegek who [sent] you.

**You say:** `seloxia`



if **Faction** >= Amiable then



>**Yegek B-Larin says:** You are a new blood!  I shall help you to face the dangers. For now, you must listen. First we must be sure to increase your skill by combat. Take this bag to the outside and fill it with three beetle eyes and three bone shards from the undead. Combine and return it. Then we shall reward you and continue. Do not lose the short sword you had upon entering our brotherhood. We just may need it later on.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/17942" data-url="17942" class="tooltip-link link">Empty Bag</a>


elseif **Faction** >= Indifferent then



>**Yegek B-Larin says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Yegek B-Larin says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.




**You say:** `second test`



if **Faction** >= Amiable then



>**Yegek B-Larin says:** You will now learn what happens to those undesirables who once called themselves Indigo. But first, you will hand me your sword which was given to you by the Indigo Brotherhood. This battle must be fought without a blade. Show us your strength!


elseif **Faction** >= Indifferent then



>**Yegek B-Larin says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Yegek B-Larin says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.






## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/13887" data-url="13887" class="tooltip-link link">Bag of Eyes n Bones</a>) then


>**Yegek B-Larin says:** Very nice work. Here are some provisions. Now are you [ready for the second test]?


Your faction standing with [Indigo Brotherhood](/faction/270) got better (<span class='text-success'>+5</span>)


Your faction standing with [Emerald Warriors](/faction/326) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Steel Warriors](/faction/311) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Primordial Malice](/faction/1522) got worse (<span class='text-danger'>-10</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_570.png" alt="" /> <a
                                href="/item/13005" data-url="13005" class="tooltip-link link">Iron Ration</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_570.png" alt="" /> <a
                                href="/item/13007" data-url="13007" class="tooltip-link link">Ration</a>) (+3000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/10830" data-url="10830" class="tooltip-link link">Sullied Two Handed Sword</a> (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 5 <img src='/static/icons/item_647.png' width='14' height='14'/> 


**This NPC *should* return incorrect items given.**






