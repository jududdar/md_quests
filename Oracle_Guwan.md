# Oracle Guwan

[Oracle Guwan](/npc/202254) is a level 61 Troll GM Shaman that spawns in [Plane of Knowledge](/zone/202).

Their primary faction is [Inhabitants of Tanaan](/faction/1636).



## Dialog

**You say:** `hail`


>*Oracle Guwan curls back his thin, reptilian-like lips, baring a two rows of jagged, unkempt teeth in a sinister sneer of hate. 'Little worm speaks? How quaint and disgusting you are, worm, and how pathetic. Begone from Kartis, little worm, you do not belong among the shadows. Your ears will melt when the shadow speaks the secrets of its mind and infinite memory. But. . . hehehe. . . but. yes. maybe you little worms think yourselves beyond the shadow's venomous tongue. . . maybe you are. . . heheheh. . . maybe you should stay, worm, and learn from Guwan. He knows much of the shadow's words, the shadow that taints and subdues the world of spirits to its will. Yes, stay worm, and learn from the shadow. . . see how. . . hehehehe. . . see how brave you truly are.'*









## Turn-Ins



local count =  **You turn in:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/4871" data-url="4871" class="tooltip-link link">Rune Etched Helm</a>, 4872, 4873, 4874, 4875, 4876, 4877 x 1

if(count > 0) then

repeat

>**Oracle Guwan says:** Thank you, Soandso.

 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 

count = count - 1;

until count == 0;



**This NPC *should* return incorrect items given.**












