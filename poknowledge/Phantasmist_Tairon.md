# Phantasmist Tairon

## Dialog

**You say:** `Hail`



if(e.other:Race() == "Dark Elf" or e.other:Race() == "Iksar" or e.other:Race() == "Troll" or e.other:Race() == "Ogre" or e.other:Class() == "Shadowknight" or e.other:Class() == "Necromancer") then



e.self:DoAnim(48)



e.self:Emote("gives a soft, though polite nod of greetings. 'You stand within the district of Tanaan 


else



e.self:DoAnim(70);



e.self:Emote("gives a deep, sweeping bow of proper and formal greetings. 'Welcome, Heiggan, to the district of Tanaan 

end

## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1124.png" alt="" /> <a
                                href="/item/1246" data-url="1246" class="tooltip-link link">Insidious Halo</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_838.png" alt="" /> <a
                                href="/item/1247" data-url="1247" class="tooltip-link link">Insidious Robe</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/1248" data-url="1248" class="tooltip-link link">Insidious Sleeves</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_671.png" alt="" /> <a
                                href="/item/1249" data-url="1249" class="tooltip-link link">Insidious Manacle</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/1250" data-url="1250" class="tooltip-link link">Insidious Gloves</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/1251" data-url="1251" class="tooltip-link link">Insidious Pantaloons</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_666.png" alt="" /> <a
                                href="/item/1252" data-url="1252" class="tooltip-link link">Insidious Slippers</a>}

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





