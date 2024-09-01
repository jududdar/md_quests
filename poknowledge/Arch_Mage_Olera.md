# Arch Mage Olera

[Arch Mage Olera](/npc/202241) is a level 61 High Elf GM Magician that spawns in [Plane of Knowledge](/zone/202).

Their primary faction is [Inhabitants of Tanaan](/faction/1636).




## Dialog
**You say:** `Hail`

>*Arch Mage Olera gives an almost unearthly graceful gesture in warm welcoming of Soandso. 'May the light of honor, valor, and untainted passion guide you through the dark turmoil of this dreaded era. I am very pleased to see you before us, friend, for the children of the light must all come together in this dark hour of Norrath and the universe's fate. If you have need of guidance in the ways of the elements, then what humble knowledge I have is at your disposal, my friend.'*




## Turn-Ins

local count =  **You turn in:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/1239" data-url="1239" class="tooltip-link link">Apothic Crown</a>, 1240, 1241, 1242, 1243, 1244, 1245 x 1
if(count > 0) then
repeat
>**Arch Mage Olera says:** Thank you, Soandso.
 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 
count = count - 1;
until count == 0;

**This NPC *should* return incorrect items given.**






