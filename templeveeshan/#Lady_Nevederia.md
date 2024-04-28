# Lady Nevederia


## On NPC Spawn

**Spawn NPC:**  [a guardian spirit](/npc/124157) at (**y:** 564, **x:** -795)
function event_death(e)


local npc_list = eq.get_entity_list():GetNPCList();



if ( npc_list ) then


for npc in npc_list.entries do



if ( npc:GetNPCTypeID() ==  [a guardian spirit](/npc/124157) and npc:GetX() == -795 and npc:GetY() == 564 ) then




npc:Depop();




break;



end
