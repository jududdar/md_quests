# Baltaldor the Cursed

[Baltaldor the Cursed](/npc/215054) is a level 67 Stormrider Warrior that spawns in [Plane of Air](/zone/215).

Their primary faction is [KOS](/faction/5017).

## Combat

if  Baltaldor the Cursed enters combat  then

**Set a timer** named *drophate* for 1 seconds

else

**Stop timer** named *drophate*











local ratio = e.self:GetHPRatio();

if ( ratio < 50 or math.random(1,100) > ratio ) then

e.self:GMMove(e.self:GetGuardPointX(), e.self:GetGuardPointY(), e.self:GetGuardPointZ(), e.self:GetSpawnPointH());

e.self:SetHP(e.self:GetHP() + math.floor(e.self:GetMaxHP() * 0.3));











## Timer(s)



if ( e.timer == "drophate") then



if ( math.random() < 0.01666 ) then 

local target = e.self:GetTarget();

if ( target and target.valid ) then

e.self:RemoveFromHateList(target);



eq.debug(e.self:GetName().." dropped target from hate list ("..target:GetName()..")", 2);





