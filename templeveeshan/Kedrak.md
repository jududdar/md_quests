# Kedrak



[Kedrak](/npc/124093) is a level 60 Drake Warrior that spawns in [Temple of Veeshan](/zone/124).




## Combat

if  Kedrak enters combat  then





local entity_list = eq.get_entity_list();





local npc_table = {124074,124094};


for k,v in pairs(npc_table) do



local npc = entity_list:GetMobByNpcTypeID(v);



if (npc.valid) then




npc:AddToHateList(e.other,1);



end