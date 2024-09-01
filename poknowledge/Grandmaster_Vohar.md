# Grandmaster Vohar

[Grandmaster Vohar](/npc/202263) is a level 61 Iksar GM Monk that spawns in [Plane of Knowledge](/zone/202).

Their primary faction is [Inhabitants of Tanaan](/faction/1636).


## Dialog
**You say:** `hail`

e.self:Emote("sneers coldly, his face contorting into a wretched, gruesome stare of hate. His eyes fill with an untamed, feral bloodlust as his low, hissing voice begins to seep from his throat. 'You stand within the district of Kartis 





## Turn-Ins

local count =  **You turn in:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_838.png" alt="" /> <a
                                href="/item/1201" data-url="1201" class="tooltip-link link">Shiverback-hide Jerkin</a>, 1202, 1203, 1204, 1205, 1206 x 1
if(count > 0) then
repeat
>**Grandmaster Vohar says:** Thank you, Soandso.
 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 
count = count - 1;
until count == 0;

**This NPC *should* return incorrect items given.**






