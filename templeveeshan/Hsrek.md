# Hsrek

[Hsrek](/npc/124014) is a level 60 Drake Warrior that spawns in [Temple of Veeshan](/zone/124).

Their primary faction is [Guardians of Veeshan](/faction/467).


## Combat
if  Hsrek enters combat  then

local entity_list = eq.get_entity_list();

local npc_table = {124013,124003};
for k,v in pairs(npc_table) do
local npc = entity_list:GetMobByNpcTypeID(v);
if (npc.valid) then
npc:AddToHateList(e.other,1);



