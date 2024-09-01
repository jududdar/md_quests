# Phantasmist Tairon

[Phantasmist Tairon](/npc/202245) is a level 61 High Elf GM Enchanter that spawns in [Plane of Knowledge](/zone/202).

Their primary faction is [Inhabitants of Tanaan](/faction/1636).



## Dialog

**You say:** `Hail`


if(e.other:Race() == "Dark Elf" or e.other:Race() == "Iksar" or e.other:Race() == "Troll" or e.other:Race() == "Ogre" or e.other:Class() == "Shadowknight" or e.other:Class() == "Necromancer") then

e.self:DoAnim(48)

e.self:Emote("gives a soft, though polite nod of greetings. 'You stand within the district of Tanaan 

else

e.self:DoAnim(70);

e.self:Emote("gives a deep, sweeping bow of proper and formal greetings. 'Welcome, Heiggan, to the district of Tanaan 











## Turn-Ins



local count =  **You turn in:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1124.png" alt="" /> <a
                                href="/item/1246" data-url="1246" class="tooltip-link link">Insidious Halo</a>, 1247, 1248, 1249, 1250, 1251, 1252 x 1

if(count > 0) then

repeat

>**Phantasmist Tairon says:** This looks good, thank you Soandso.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 

count = count - 1;

until count == 0;



**This NPC *should* return incorrect items given.**












