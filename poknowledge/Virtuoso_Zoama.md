# Virtuoso Zoama



[Virtuoso Zoama](/npc/202009) is a level 61 Wood Elf GM Bard that spawns in [Plane of Knowledge](/zone/202).





## Dialog

**You say:** `Hail`



>*Virtuoso Zoama gives a warm smile of her comely features and a delicate bow of her head in greetings. 'Good day to you, Soandso, and welcome to the district of Selia. You will find that the light and mortal virtues of justly kindness, honor, valor, and untainted passion are represented in full upon this plane in our midst. Rather, each of the three districts that house the adepts of New Tanaan represent and fulfill the core elements and pure essence of mortal virtues within the universe, we collectively embody that of the light. I'm certain you will find yourself at home among us, and for this we are pleased and grateful. During your stay with us, I would suggest that you seek our adepts and merchants, for the knowledge we hold cannot be found in the library of Myrist. for it is one that is the key to purity and faith of the light. If you are one of the bardic traditions, then I may be of assistance to you should you need training the ways of your skills. Otherwise, it has been a pleasure to make your acquaintance.'*
end



## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/4861" data-url="4861" class="tooltip-link link">Imbrued Platemail Helm</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_624.png" alt="" /> <a
                                href="/item/4862" data-url="4862" class="tooltip-link link">Imbrued Platemail Breastplate</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_622.png" alt="" /> <a
                                href="/item/4863" data-url="4863" class="tooltip-link link">Imbrued Platemail Vambraces</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/4864" data-url="4864" class="tooltip-link link">Imbrued Platemail Bracer</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_531.png" alt="" /> <a
                                href="/item/4865" data-url="4865" class="tooltip-link link">Imbrued Platemail Gauntlets</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_540.png" alt="" /> <a
                                href="/item/4866" data-url="4866" class="tooltip-link link">Imbrued Platemail Greaves</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_524.png" alt="" /> <a
                                href="/item/4867" data-url="4867" class="tooltip-link link">Imbrued Platemail Boots</a>}

if(count > 0) then


repeat



>**Virtuoso Zoama says:** Thank you, Soandso.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





