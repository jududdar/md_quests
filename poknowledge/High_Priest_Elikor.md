# High Priest Elikor



## Dialog

**You say:** `Hail`



e.self:Emote("raises a brow sharply, his beautiful features contorting into a flawless mask of regal superiority and a meager amusement in disdain toward Soandso. 'I see that the ranting of Selia's zealous crusaders of 'passion and honor' have become even too much for those who once believed themselves of the same cause. Indeed, how marvelously intriguing. Perhaps now you reside in Kartis to bathe in the cold embrace of the shadow 
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



>**High Priest Elikor says:** Thank you, Soandso.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**




## On NPC Spawn

x = e.self:GetX();

y = e.self:GetY();

eq.set_proximity(x - 90, x + 90, y - 90, y + 90);
function event_enter(e)

**Signaled to:** 202273




