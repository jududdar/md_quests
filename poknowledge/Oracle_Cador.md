# Oracle Cador



[Oracle Cador](/npc/202239) is a level 61 Barbarian GM Shaman that spawns in [Plane of Knowledge](/zone/202).




## Dialog

**You say:** `Hail`



e.self:Emote("gives a stiff nod in proper greetings to Soandso. 'The light of Selia shines in welcoming, friend. If you seek supplies or training, know that Selia will accommodate your every need in these specific areas most efficiently 

**You say:** `black lava powder`



>**Oracle Cador says:** You are most astute. I do have a stock of black lava powder with me, but I will only share it with those who prove themselves worthy. Onirelin Gali is currently in possession of an artifact I need to better commune with the spirits. Please recover it for me.
end



## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/4871" data-url="4871" class="tooltip-link link">Rune Etched Helm</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_624.png" alt="" /> <a
                                href="/item/4872" data-url="4872" class="tooltip-link link">Rune Etched Chestplate</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_622.png" alt="" /> <a
                                href="/item/4873" data-url="4873" class="tooltip-link link">Rune Etched Vambraces</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/4874" data-url="4874" class="tooltip-link link">Rune Etched Bracer</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_531.png" alt="" /> <a
                                href="/item/4875" data-url="4875" class="tooltip-link link">Rune Etched Gauntlets</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_540.png" alt="" /> <a
                                href="/item/4876" data-url="4876" class="tooltip-link link">Rune Etched Greaves</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_524.png" alt="" /> <a
                                href="/item/4877" data-url="4877" class="tooltip-link link">Rune Etched Boots</a>}

if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_894.png" alt="" /> <a
                                href="/item/28089" data-url="28089" class="tooltip-link link">Cadors Artifact</a>) then


>**Oracle Cador says:** The spirits are restful now that this piece of legend is in safe hands. You may take this to Mirao for whatever purpose he desires it for. May your vision always be clear!





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_733.png" alt="" /> <a
                                href="/item/28090" data-url="28090" class="tooltip-link link">Black Lava Powder</a> (+100 exp)

 

if(count > 0) then


repeat



>**Oracle Cador says:** Thank you, Soandso.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**
