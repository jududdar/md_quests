# Belijor the Emerald Eye



[Belijor the Emerald Eye](/npc/124057) is a level 63 Drake Warrior that spawns in [Temple of Veeshan](/zone/124).




## Combat

if  Belijor the Emerald Eye enters combat  then





local entity_list = eq.get_entity_list();








local npc_table = {124017,124056,124088,124089};


for k,v in pairs(npc_table) do



local npc = entity_list:GetMobByNpcTypeID(v);



if (npc.valid) then




npc:AddToHateList(e.other,1);



end