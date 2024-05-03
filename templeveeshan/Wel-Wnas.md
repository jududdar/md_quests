# Wel-Wnas



## Combat

if  Wel-Wnas enters combat  then





local entity_list = eq.get_entity_list();





local npc_table = {124077,124091};


for k,v in pairs(npc_table) do



local npc = entity_list:GetMobByNpcTypeID(v);



if (npc.valid) then




npc:AddToHateList(e.other,1);



end