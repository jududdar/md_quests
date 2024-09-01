# abandoned heretic pet

[abandoned heretic pet](/npc/38012) is a level 7 Skeleton Warrior that spawns in [Toxxulia Forest](/zone/38).

Their primary faction is [Noobie Monsters KOS to Guards](/faction/5023).

## Arrive at Waypoint Script
if(e.wp == 5) then
if(**spawned NPC:**  [\#a skeleton](/npc/38009) or **spawned NPC:**  [\#\#a skeleton](/npc/38010)) then
>**abandoned heretic pet says:** Speed up the digging my pets!
if(**spawned NPC:**  [\#a skeleton](/npc/38009)) then
eq.get_entity_list():GetMobByNpcTypeID(38009):Say("We are not your pets!");

if(**spawned NPC:**  [\#\#a skeleton](/npc/38010)) then
eq.get_entity_list():GetMobByNpcTypeID(38010):Say("We will speed up when you return our mining caps. There are falling rocks all over this place! We could get killed!");


elseif(e.wp == 7) then
>**abandoned heretic pet says:** Blast you, skeletons!  Why I ever resurrected you, I don't know!






## Turn-Ins

if( **You turn in:**   <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_639.png" alt="" /> <a
                                href="/item/13894" data-url="13894" class="tooltip-link link">Useless Cloth Cap</a> ) then
>**abandoned heretic pet says:** Good work, you should be running this operation instead of that Talrigar fellow. Have a small reward. A little bit of the gems I found while tunneling through this rock.
 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_944.png" alt="" /> <a
                                href="/item/10015" data-url="10015" class="tooltip-link link">Malachite</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_945.png" alt="" /> <a
                                href="/item/10016" data-url="10016" class="tooltip-link link">Lapis Lazuli</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_946.png" alt="" /> <a
                                href="/item/10017" data-url="10017" class="tooltip-link link">Turquoise</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_767.png" alt="" /> <a
                                href="/item/10018" data-url="10018" class="tooltip-link link">Hematite</a>) (+500 exp)

 

**This NPC *should* return incorrect items given.**

