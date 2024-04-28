# A Mystical Arbitor of Earth
local PLANAR_PROJECTION_TYPE = 218398;

## On NPC Spawn

**Set a timer** named *depop* for 3000 seconds
## Combat

if  A Mystical Arbitor of Earth enters combat  then


**Set a timer** named *drophate* for 1 seconds

else


**Stop timer** named *drophate*

















local ratio = e.self:GetHPRatio();


if ( ratio < 50 or math.random(100) > ratio ) then



e.self:GMMove(e.self:GetGuardPointX(), e.self:GetGuardPointY(), e.self:GetGuardPointZ(), e.self:GetSpawnPointH());



e.self:SetHP(e.self:GetHP() + math.floor(e.self:GetMaxHP() * 0.3));

end

## Timer(s)

if ( e.timer == "drophate") then



if ( math.random() < 0.05 ) then 



local target = e.self:GetTarget();



if ( target and target.valid ) then




e.self:RemoveFromHateList(target);





eq.debug(e.self:GetName().." dropped target from hate list ("..target:GetName()..")", 2);




elseif ( e.timer == "depop" ) then


eq.debug("Arbitor depop");


**A Mystical Arbitor of Earth despawns.**
end

## On NPC Death

eq.spawn2(PLANAR_PROJECTION_TYPE, 0, 0, e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0);

eq.signal(PLANAR_PROJECTION_TYPE, e.killer:GetID()); 