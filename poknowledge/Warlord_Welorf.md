# Warlord Welorf

## Dialog

**You say:** `Hail`



>*Warlord Welorf gathers a deep breath, his body seeming unnaturally stiff within the large suit of iron. His cold, steely eyes glance over you once before addressing you in a low, baritone voice. 'You stand before Welorf, Warlord of the North and former chief of the Steel Warrior's clan. Should you be a warrior, the knowledge of my blade is at your reach and perhaps in time, and with some training, a proper warrior can borne of the weak creature I see before me.'*
end

## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/4911" data-url="4911" class="tooltip-link link">Indicolite Helm</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_624.png" alt="" /> <a
                                href="/item/4912" data-url="4912" class="tooltip-link link">Indicolite Breastplate</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_622.png" alt="" /> <a
                                href="/item/4913" data-url="4913" class="tooltip-link link">Indicolite Vambraces</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/4914" data-url="4914" class="tooltip-link link">Indicolite Bracer</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_531.png" alt="" /> <a
                                href="/item/4915" data-url="4915" class="tooltip-link link">Indicolite Gauntlets</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_540.png" alt="" /> <a
                                href="/item/4916" data-url="4916" class="tooltip-link link">Indicolite Greaves</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_524.png" alt="" /> <a
                                href="/item/4917" data-url="4917" class="tooltip-link link">Indicolite Boots</a>}

if(count > 0) then


repeat



>**Warlord Welorf says:** Thank you, Soandso.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





