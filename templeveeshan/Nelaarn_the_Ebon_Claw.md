# Nelaarn the Ebon Claw



[Nelaarn the Ebon Claw](/npc/124089) is a level 63 Drake Warrior that spawns in [Temple of Veeshan](/zone/124).




## Combat

if  Nelaarn the Ebon Claw enters combat  then





local entity_list = eq.get_entity_list();








local npc_table = {124017,124056,124057,124088};


for k,v in pairs(npc_table) do



local npc = entity_list:GetMobByNpcTypeID(v);



if (npc.valid) then




npc:AddToHateList(e.other,1);



end