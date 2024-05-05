# Reania Jukle



[Reania Jukle](/npc/45082) is a level 61 Human GM Enchanter that spawns in [Qeynos Aqueduct System](/zone/45).



## Dialog

**You say:** `hail`



>**Reania Jukle says:** Greetings, Soandso. What can I help you with?

**You say:** `what is the ink of the dark`



>**Reania Jukle says:** Ink of the Dark, you say? That isn't an everyday item, you know. In fact, I can't remember the last time someone requested it. I have given up keeping any here with me. You are going to need to find your own supply now. Sorry.

**You say:** `find the ink of the dark`



>**Reania Jukle says:** The ink is the blood of a dark scribe. Tempt him and give him this vial. He should cooperate.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_585.png" alt="" /> <a
                                href="/item/10626" data-url="10626" class="tooltip-link link">Empty Ink Vial</a>


local enchant_bars_lib = require("self_found_enchant_bars");

enchant_bars_lib.check_bars_quest_dialogue(e.self, e.other, e.message);


## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/18851" data-url="18851" class="tooltip-link link">Blood Stained Note</a>) then 


Your faction standing with [Bloodsabers](/faction/221) got better (<span class='text-success'>+100</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got better (<span class='text-success'>+10</span>)


Your faction standing with [Priests of Life](/faction/341) got worse (<span class='text-danger'>-25</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_928.png" alt="" /> <a
                                href="/item/13596" data-url="13596" class="tooltip-link link">Dirty Purple Robe*</a> (+20 exp)

 


local enchant_bars_lib = require("self_found_enchant_bars");

enchant_bars_lib.check_for_bars_to_enchant(item_lib, e.self, e.other, e.trade);


**This NPC *should* return incorrect items given.**
;





