# Warlord Gintolaken



[Warlord Gintolaken](/npc/222038) is a level 77 Giant Warrior that spawns in [Plane of Earth](/zone/222).

local BOSS_TYPES = { 222035, 222037, 222036, 222008, 222009, 222010 }; 



## On NPC Spawn

**Set a timer** named *check* for 1 seconds


## Combat

if  Warlord Gintolaken enters combat  then


**Set a timer** named *drophate* for 1 seconds

else


**Stop timer** named *drophate*

















local ratio = e.self:GetHPRatio();


if ( ratio < 50 or math.random(100) > ratio ) then



e.self:GMMove(e.self:GetGuardPointX(), e.self:GetGuardPointY(), e.self:GetGuardPointZ(), e.self:GetSpawnPointH());



e.self:SetHP(e.self:GetHP() + math.floor(e.self:GetMaxHP() * 0.3));

end



## Timer(s)

if ( e.timer == "drophate" ) then




if ( e.self:GetX() < -137 ) then



e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());



**Warlord Gintolaken** clears hate list.



**Warlord Gintolaken casts:** [Balance of the Nameless](/spell/3230) on themselves.



return;






if ( math.random() < 0.03333 ) then 



local target = e.self:GetTarget();



if ( target and target.valid ) then




e.self:RemoveFromHateList(target);





eq.debug(e.self:GetName().." dropped target from hate list ("..target:GetName()..")", 2);




elseif ( e.timer == "check" ) then


eq.stop_timer(e.timer);






local elist = eq.get_entity_list();


for _, id in ipairs(BOSS_TYPES) do



if ( elist:IsMobSpawnedByNpcTypeID(id) ) then




**Warlord Gintolaken despawns.**




return;



end



## On NPC Death

eq.get_entity_list():GetSpawnByID(369490):GetNPC():Depop(true);

eq.get_entity_list():GetSpawnByID(369490):SetTimer(302400000);