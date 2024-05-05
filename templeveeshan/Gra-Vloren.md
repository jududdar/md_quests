# Gra\`Vloren



[Gra\`Vloren](/npc/124091) is a level 60 Drake Warrior that spawns in [Temple of Veeshan](/zone/124).




## Combat

if  Gra-Vloren enters combat  then





local entity_list = eq.get_entity_list();





local npc_table = {124077,124092};


for k,v in pairs(npc_table) do



local npc = entity_list:GetMobByNpcTypeID(v);



if (npc.valid) then




npc:AddToHateList(e.other,1);



end