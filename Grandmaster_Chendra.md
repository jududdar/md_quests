# Grandmaster Chendra

[Grandmaster Chendra](/npc/202011) is a level 61 Human GM Monk that spawns in [Plane of Knowledge](/zone/202).

Their primary faction is [Inhabitants of Tanaan](/faction/1636).



## Dialog

**You say:** `Hail`


>*Grandmaster Chendra gives a deep-seated bow of respect and humble greetings. Her voice is gentle and calm, like the soothing melody of a grandmother with the youth of a newborn wind. 'Greetings, my friend, and may the light watch over your path. The district of Selia is one of light and upholds its virtues fervently, though we do not seek to impose upon others in our humble plane. You will find many whom, upon your world, are enemies but here, though they look upon you with disdain, are ultimately your equals in the quest for knowledge and enlightenment. If you are a student of the disciplines of the monk, then I shall lend my knowledge to you whenever you are in need of lessons in the martial skills of our order.'*









## Turn-Ins



local count =  **You turn in:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_838.png" alt="" /> <a
                                href="/item/1201" data-url="1201" class="tooltip-link link">Shiverback-hide Jerkin</a>, 1202, 1203, 1204, 1205, 1206 x 1

if(count > 0) then

repeat

>**Grandmaster Chendra says:** Thank you, Soandso.

 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 

count = count - 1;

until count == 0;



**This NPC *should* return incorrect items given.**












