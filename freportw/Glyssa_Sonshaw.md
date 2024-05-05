# Glyssa Sonshaw



[Glyssa Sonshaw](/npc/9067) is a level 61 Erudite GM Enchanter that spawns in [West Freeport](/zone/9).




## Dialog

local enchant_bars_lib = require("self_found_enchant_bars");

enchant_bars_lib.check_bars_quest_dialogue(e.self, e.other, e.message);


## Turn-Ins



local text = "I require the parchment from Leraena as well as the Odd Cold Iron Necklace.";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/1772" data-url="1772" class="tooltip-link link">Sealed Parchment</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_566.png" alt="" /> <a
                                href="/item/14585" data-url="14585" class="tooltip-link link">Odd Cold Iron Necklace</a>) then 


>**Glyssa Sonshaw says:** Ah..yes, I have seen this symbol before. There is a kobold that lives among the gnomes of Ak'anon. He may be reluctant to speak with you but you have no need to fear him. He is a follower of Brell Serilis and a valuable source of information on kobold society and culture. I will construct a message for him. Deliver the message and necklace and perhaps he can enlighten you to its meaning.


Your faction standing with [Arcane Scientists](/faction/220) got better (<span class='text-success'>+10</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+2</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_566.png" alt="" /> <a
                                href="/item/14585" data-url="14585" class="tooltip-link link">Odd Cold Iron Necklace</a> (+1000 exp)

 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/1779" data-url="1779" class="tooltip-link link">Sealed Parchment</a> 

 


local enchant_bars_lib = require("self_found_enchant_bars");


enchant_bars_lib.check_for_bars_to_enchant(item_lib, e.self, e.other, e.trade);


**This NPC *should* return incorrect items given.**


