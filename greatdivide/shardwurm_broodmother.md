# shardwurm broodmother
## Turn-Ins




if(e.self:GetX() == -1164 and e.self:GetY() == -3301 and e.self:GetGrid() == 0) then


if( **You turn in:** [Harness of Control](/item/30272)) then 



>*shardwurm broodmother reels in pain as the harness snaps around its neck tightly. A strange gleam enters its eyes as it slowly begins to shamble towards the exit and the giants fortress.*



 **You receive:** 0 (+20000 exp)







eq.start(54);


elseif( **You turn in:** [Giants Harness of Control](/item/30274)) then 



>*shardwurm broodmother reels in pain as the harness snaps around its neck tightly.  A strange gleam enters its eyes as it slowly begins to shamble towards the exit and the Coldain mines.*



 **You receive:** 0 (+20000 exp)



**Set a timer** named *korf* for 90 seconds







eq.start(56);


**This NPC *should* return incorrect items given.**
;
## Arrive at Waypoint Script






if(e.wp == 13 and e.self:GetGrid() == 54) then





eq.set_proximity(-2020-65,-2020+65,-2453-65,-2453+65);

elseif(e.wp == 17 and e.self:GetGrid() == 56) then


if(**spawned NPC:**  [\#Relik](/npc/118018)) then



**shardwurm broodmother attacks NPC:**  [\#Relik](/npc/118018)



if(**spawned NPC:**  [Korf Brokenhammer ](/npc/118019)) then



**Despawn NPC:**  [Korf Brokenhammer ](/npc/118019)



**Spawn NPC:**  [\#Korf Brokenhammer](/npc/118020) at (**y:** -6207, **x:** -3194)



elseif(e.wp == 19 and e.self:GetGrid() == 54) then





eq.clear_proximity();


if(**spawned NPC:**  [\#Gralk Dwarfkiller](/npc/118012)) then



**shardwurm broodmother attacks NPC:**  [\#Gralk Dwarfkiller](/npc/118012)



eq.get_entity_list():GetMobByNpcTypeID( [\#Fergul Frostsky](/npc/118015)):SetRunning(true);



eq.get_entity_list():GetMobByNpcTypeID( [\#Fergul Frostsky](/npc/118015)):CastToNPC():AssignWaypoints(55);

end


function event_enter(e)

**Spawn NPC:**  [\#Fergul Frostsky](/npc/118015) at (**y:** -2615, **x:** -2397)

**Spawn NPC:**  [\#Gralk Dwarfkiller](/npc/118012) at (**y:** -2569, **x:** -2391)

eq.clear_proximity();
## Timer(s)

if(e.timer == "korf") then


**Spawn NPC:**  [\#Relik](/npc/118018) at (**y:** -6187, **x:** -3171)


**Spawn NPC:**  [Korf Brokenhammer ](/npc/118019) at (**y:** -6207, **x:** -3194)


**Stop timer** named *korf*
end