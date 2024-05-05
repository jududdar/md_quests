# Konious Eranon



[Konious Eranon](/npc/10120) is a level 61 Human GM Enchanter that spawns in [East Freeport](/zone/10).



## Dialog

**You say:** `hail`



>**Konious Eranon says:** Greetings!  I am the mighty Konious Eranon, Master Enchanter, devoted follower of Innoruuk, and loyal assistant to the all-powerful Nexvok.

local enchant_bars_lib = require("self_found_enchant_bars");

enchant_bars_lib.check_bars_quest_dialogue(e.self, e.other, e.message);


## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18856" data-url="18856" class="tooltip-link link">A tattered note</a>) then 


>**Konious Eranon says:** Hey, Nex, we got another sucker.. er.. volunteer, that is, to help us out around here. Here ya go friend, put this on and let's whip you into shape.


Your faction standing with [Dismal Rage](/faction/271) got better (<span class='text-success'>+100</span>)


Your faction standing with [Knights of Truth](/faction/281) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got better (<span class='text-success'>+20</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_930.png" alt="" /> <a
                                href="/item/13566" data-url="13566" class="tooltip-link link">Blood Spotted Robe*</a> (+20 exp)

 


local enchant_bars_lib = require("self_found_enchant_bars");

enchant_bars_lib.check_for_bars_to_enchant(item_lib, e.self, e.other, e.trade);


**This NPC *should* return incorrect items given.**





