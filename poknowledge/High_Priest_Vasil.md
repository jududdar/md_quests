# High Priest Vasil

## Dialog

**You say:** `Hail`



>*High Priest Vasil closes his eyes and gives a deep, formal bow before Soandso. 'Welcome to Jeral, friend. I am Vasil, High Priest of Brell Serillis and resident master of the clerical arts in the district of Tanaan. If you have come in search of a mentor to guide you through the skills of your priesthood, then do not be discouraged by my own declaration of faith should it differ from yours. I cannot teach you how to know and be close to your deity in life, for only you may know that individually, but I can impart to you the fundamental basics that every priest, despite the object of their undying faith and devotion, wields in their life of service.'*
end

## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/4881" data-url="4881" class="tooltip-link link">Ethereal Mist Helm</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_624.png" alt="" /> <a
                                href="/item/4882" data-url="4882" class="tooltip-link link">Ethereal Mist Chestplate</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_622.png" alt="" /> <a
                                href="/item/4883" data-url="4883" class="tooltip-link link">Ethereal Mist Vambraces</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/4884" data-url="4884" class="tooltip-link link">Ethereal Mist Bracers</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_531.png" alt="" /> <a
                                href="/item/4885" data-url="4885" class="tooltip-link link">Ethereal Mist Gauntlets</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_540.png" alt="" /> <a
                                href="/item/4886" data-url="4886" class="tooltip-link link">Ethereal Mist Greaves</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_524.png" alt="" /> <a
                                href="/item/4887" data-url="4887" class="tooltip-link link">Ethereal Mist Boots</a>}

if(count > 0) then


repeat



>**High Priest Vasil says:** Thank you, Soandso.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





