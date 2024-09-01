# Oracle Maeth

[Oracle Maeth](/npc/202246) is a level 61 Barbarian GM Shaman that spawns in [Plane of Knowledge](/zone/202).

Their primary faction is [Inhabitants of Tanaan](/faction/1636).



## Dialog

**You say:** `hail`


>*Oracle Maeth makes a sweeping motion with his arms in an almost ritualistic fashion of greetings known only to those of the shamanistic world. 'We welcome you, friend, to the Tanaan district of the Plane of Knowledge. Beyond a seemingly endless fount of tangible supplies, the adepts of Jeral have come together and offered to retake our former duties as guildmasters and mentors to those of our art. In my life before New Tanaan's embrace of me, I served as one of many shamans of the Northmen, before Halas' walls were secured in the turmoil of the frozen north. As the years passed and years fell way to decades, I ascended to hold the seat of guild master of my order and have mentored countless shamans in my day. If you are in need of such knowledge, then please, do not hesitate in acquiring my aid.'*









## Turn-Ins



local count =  **You turn in:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/4871" data-url="4871" class="tooltip-link link">Rune Etched Helm</a>, 4872, 4873, 4874, 4875, 4876, 4877 x 1

if(count > 0) then

repeat

>**Oracle Maeth says:** Thank you, Soandso.

 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 

count = count - 1;

until count == 0;



**This NPC *should* return incorrect items given.**












