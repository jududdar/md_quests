# Eashen of the Sky



[Eashen of the Sky](/npc/124017) is a level 66 Drake Warrior that spawns in [Temple of Veeshan](/zone/124).




## Combat

if  Eashen of the Sky enters combat  then





local entity_list = eq.get_entity_list();








local npc_table = {124056,124057,124088,124089};


for k,v in pairs(npc_table) do



local npc = entity_list:GetMobByNpcTypeID(v);



if (npc.valid) then




npc:AddToHateList(e.other,1);



end