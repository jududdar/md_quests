# Lord Koi\`Doken



[Lord Koi\`Doken](/npc/124103) is a level 66 Dragon Rogue that spawns in [Temple of Veeshan](/zone/124).





## On NPC Spawn

**Spawn NPC:**  [a guardian spirit](/npc/124157) at (**y:** 509, **x:** -679)
function event_death(e)


local npc_list = eq.get_entity_list():GetNPCList();



if ( npc_list ) then


for npc in npc_list.entries do



if ( npc:GetNPCTypeID() ==  [a guardian spirit](/npc/124157) and npc:GetX() == -679 and npc:GetY() == 509 ) then




npc:Depop();




break;



end
