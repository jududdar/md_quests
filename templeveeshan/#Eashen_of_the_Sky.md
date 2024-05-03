# Eashen of the Sky



## Combat

if  Eashen of the Sky enters combat  then





local entity_list = eq.get_entity_list();








local npc_table = {124056,124057,124088,124089};


for k,v in pairs(npc_table) do



local npc = entity_list:GetMobByNpcTypeID(v);



if (npc.valid) then




npc:AddToHateList(e.other,1);



end