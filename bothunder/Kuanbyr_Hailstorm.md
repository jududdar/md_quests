# Kuanbyr Hailstorm



[Kuanbyr Hailstorm](/npc/209061) is a level 67 Giant Warrior that spawns in [Bastion of Thunder](/zone/209).

local TYPES = { 209058, 209057, 209056 }; 



## Combat

if  Kuanbyr Hailstorm enters combat  then


**Set a timer** named *tick* for 6 seconds

else


**Stop timer** named *tick*
end



## Timer(s)


if ( e.timer == "tick" ) then




local npc;





for _, id in ipairs(TYPES) do





npc = eq.get_entity_list():GetNPCByNPCTypeID(id);







if ( npc and npc.valid and e.self:GetTarget() and e.self:GetTarget().valid ) then




npc:AddToHateList(e.self:GetTarget(), 1);








if ( e.self:GetY() > -1800 ) then



e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());

end
