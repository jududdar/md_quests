# High Priest of Ssraeshza


local ADD_TYPES = { 162115, 162112, 162114, 162113, 162121, 162119, 162122, 162120, 162118, 162116, 162117, 162111 };

## Combat

if  High Priest of Ssraeshza enters combat  then


**Set a timer** named *check* for 10 seconds

else


**Stop timer** named *check*
end

## Timer(s)

if ( e.timer == "check" ) then




local elist = eq.get_entity_list();


local npc;





for _, typ in ipairs(ADD_TYPES) do



npc = elist:GetMobByNpcTypeID(typ):CastToNPC();



if ( npc and npc.valid and npc:GetZ() < 240 ) then




npc:GMMove(npc:GetSpawnPointX(), npc:GetSpawnPointY(), npc:GetSpawnPointZ(), npc:GetSpawnPointH());




npc:CastSpell(3230, npc:GetID()); 




npc:WipeHateList();




return; 



end
