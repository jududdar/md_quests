# Assassin Mirot

[Assassin Mirot](/npc/202321) is a level 61 Dark Elf GM Rogue that spawns in [Plane of Knowledge](/zone/202).

Their primary faction is [Inhabitants of Tanaan](/faction/1636).





## Dialog

**You say:** `Hail`


e.self:Emote("gives a sharply raised brow and cruelly wicked smirk, his comely features contorted in a sinister mask of disgust and amusement. 'Well, how charming of you to find it within your heart to visit Kartis, my dear pathetic Soandso. Do not think that you will be received in the manner you had hoped, for we are in the city of knowledge where tolerance for all beings to one extent or another is mandatory. Aaaah, yes, we will tolerate your existence among us, but only for the amusement of watching you squirm uncomfortably when presented with the truth of our purpose. Even further the amusement would stretch is if you would have the audacity to train from one of our adepts 









## Turn-Ins



local count =  **You turn in:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/4901" data-url="4901" class="tooltip-link link">Woven Shadow Helm</a>, 4902, 4903, 4904, 4905, 4906, 4907 x 1

if(count > 0) then

repeat

>**Assassin Mirot says:** Thank you, Soandso.

 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 

count = count - 1;

until count == 0;



**This NPC *should* return incorrect items given.**












