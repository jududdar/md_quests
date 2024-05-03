# Lord Mithaniel Marr
local PLANAR_PROJECTION_TYPE = 220025;

local SPAWNIDS = { 367227, 366604, 367163 };



## On NPC Death

eq.spawn2(PLANAR_PROJECTION_TYPE, 0, 0, e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0);

eq.signal(PLANAR_PROJECTION_TYPE, e.killer:GetID()); 


## On NPC Spawn

local elist = eq.get_entity_list();



for _, id in ipairs(SPAWNIDS) do


elist:GetSpawnByID(id):SetTimer(1);
end



## Signals


if ( e.signal == 1 ) then


**Set a timer** named *check* for 3 seconds




elseif ( e.signal == 2 ) then


e.self:SetBodyType(11, false);   


e.self:SetSpecialAbility(24, 1); 


e.self:SetSpecialAbility(35, 1); 
end



## Combat

if  Lord Mithaniel Marr enters combat  then


**Set a timer** named *bounds* for 5 seconds

else


**Stop timer** named *bounds*
end



## Timer(s)


if ( e.timer == "bounds" ) then


if ( e.self:GetX() < 2200 ) then



e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());



**Lord Mithaniel Marr** clears hate list.



**Lord Mithaniel Marr casts:** [Balance of the Nameless](/spell/3230) on themselves.




elseif ( e.timer == "check" ) then


eq.stop_timer(e.timer);





local npc;


local killed = 0;


local elist = eq.get_entity_list();





for _, id in ipairs(SPAWNIDS) do






npc = elist:GetSpawnByID(id):GetNPC();



if ( not npc or not npc.valid ) then




killed = killed + 1;








if ( killed == 3 ) then



e.self:SetBodyType(1, false);   



e.self:SetSpecialAbility(24, 0); 



e.self:SetSpecialAbility(35, 0); 

end
