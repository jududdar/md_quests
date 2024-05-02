# Crusader Difur

## Dialog

**You say:** `Hail`



>*Crusader Difur kneels before Soandso in humble recognition. The clang of his spotless, dwarven crafted armor against the stone floor briefly chimes through the hall. The song of steel and marble is echoed by his gruff, iron voice. 'I am Difur, Crusader of Brell Serillis and master of the paladins in the district of Tanaan. If ye seek knowledge and wisdom of the justly knights of Norrath than I, most humbly, am at yer service, traveler.'*
end

## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/4851" data-url="4851" class="tooltip-link link">Valorium Helmet</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_624.png" alt="" /> <a
                                href="/item/4852" data-url="4852" class="tooltip-link link">Valorium Chestplate</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_622.png" alt="" /> <a
                                href="/item/4853" data-url="4853" class="tooltip-link link">Valorium Vambraces</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/4854" data-url="4854" class="tooltip-link link">Valorium Bracers</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_531.png" alt="" /> <a
                                href="/item/4855" data-url="4855" class="tooltip-link link">Valorium Gauntlets</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_540.png" alt="" /> <a
                                href="/item/4856" data-url="4856" class="tooltip-link link">Valorium Greaves</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_524.png" alt="" /> <a
                                href="/item/4857" data-url="4857" class="tooltip-link link">Valorium Boots</a>}

if(count > 0) then


repeat



>**Crusader Difur says:** Thank you, Soandso.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





