# Yendilor the Cerulean Wing

## Combat

if  Yendilor the Cerulean Wing enters combat  then





local entity_list = eq.get_entity_list();








local npc_table = {124017,124057,124088,124089};


for k,v in pairs(npc_table) do



local npc = entity_list:GetMobByNpcTypeID(v);



if (npc.valid) then




npc:AddToHateList(e.other,1);



end