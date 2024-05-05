# Gindan Flayer



[Gindan Flayer](/npc/214084) is a level 68 Rallos Zek Minion Warrior that spawns in [Drunder, the Fortress of Zek](/zone/214).



## On NPC Spawn

if ( e.self:GetSpawnPointID() == 0 ) then 


**Set a timer** named *depop* for 360 seconds


e.self:SetSpecialAbility(49, 1);

end



## Timer(s)


if ( e.timer == "checkhp" ) then




if ( e.self:GetHPRatio() < 50 ) then



if ( math.random(100) < 25 ) then





eq.stop_timer(e.timer);



else




**Spawn NPC:**  [Gindan Flayer](/npc/214084) at this location.




**Spawn NPC:**  [Gindan Flayer](/npc/214084) at this location.




**Gindan Flayer despawns.**







elseif ( e.timer == "depop" ) then


**Gindan Flayer despawns.**
end



## Combat

if  Gindan Flayer enters combat  then


eq.pause_timer("depop");


if ( e.self:GetSpawnPointID() > 0 ) then



**Set a timer** named *checkhp* for 5 seconds












if ( e.self:GetZ() > 156 and e.self:GetX() > 0 ) then



local t = e.self:GetTarget();







if ( t and t.valid and t:GetZ() < 100 and t:GetX() < 600 ) then





local types = { 214313, 214320, 214311 };





for _, id in ipairs(types) do





if ( eq.get_entity_list():IsMobSpawnedByNpcTypeID(id) ) then













local mob = eq.get_entity_list():GetMobByNpcTypeID(id);






e.self:GMMove(mob:GetX(), mob:GetY(), mob:GetZ(), 0);






if ( t:IsClient() ) then







t:CastToClient():MovePC(214, mob:GetX(), mob:GetY(), mob:GetZ(), 0);











break;











else


eq.resume_timer("depop");
end



## Signals



if ( e.signal == e.self:GetID() ) then


**Set a timer** named *checkhp* for 5 seconds


**Stop timer** named *depop*
end
