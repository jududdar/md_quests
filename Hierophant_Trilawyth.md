# Hierophant Trilawyth

[Hierophant Trilawyth](/npc/202240) is a level 61 Wood Elf GM Druid that spawns in [Plane of Knowledge](/zone/202).

Their primary faction is [Inhabitants of Tanaan](/faction/1636).



## Dialog

**You say:** `Hail`


>*Hierophant Trilawyth gives a gentle bow of his head in respect toward Soandso. 'The district of Tanaan welcomes you, traveler. The adepts of the city have come together collectively and as individuals in hopes of aiding our visitors as we are able. In my time upon Norrath, I served as a child of nature dedicated to Tunare, the Mother of All. Though my faith has not wavered and my philosophies of nature have only grown in this astral city, I am able to train any druid who is in need of gaining a better grasp upon their skills. Mind you, however, that I am not a preacher and will not guide you through the instruction of faith or spell, for it is these things you must acquire and perfect through your own trials.'*









## Turn-Ins



local count =  **You turn in:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/3801" data-url="3801" class="tooltip-link link">Vermiculated Crown</a>, 3802, 3803, 3804, 3805, 3806, 3807 x 1

if(count > 0) then

repeat

>**Hierophant Trilawyth says:** Thank you, Soandso.

 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 

count = count - 1;

until count == 0;



**This NPC *should* return incorrect items given.**












