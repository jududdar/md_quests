# Teloa



[Teloa](/npc/15170) is a level 51 Half Elf Druid that spawns in [Eastern Plains of Karana](/zone/15).



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1053.png" alt="" /> <a
                                href="/item/20451" data-url="20451" class="tooltip-link link">Frayed Braided Grass Amulet</a>) then


>*Teloa begins walking toward the gathering spot. 'Follow, friend.'*


eq.start(12);

**This NPC *should* return incorrect items given.**



## Arrive at Waypoint Script

if(e.wp == 2) then


**Signaled to:**  [Althele](/npc/15044)


**Signaled to:**  [Nuien](/npc/15167)


**Signaled to:**  [Sionae](/npc/15178)


**Signaled to:**  [Tholris](/npc/15043)

elseif(e.wp == 3) then


**Spawn NPC:**  [Dark Elf Corruptor](/npc/15153) at (**y:** -1529, **x:** -996)


**Spawn NPC:**  [Dark Elf Reaver](/npc/15150) at (**y:** -1529, **x:** -1090)


**Spawn NPC:**  [Dark Elf Reaver](/npc/15000) at (**y:** -1490, **x:** -1063)

elseif(e.wp == 4) then


**Despawn NPC:**  [Sionae](/npc/15178)


**Despawn NPC:**  [Nuien](/npc/15167)


**Teloa despawns.**


end