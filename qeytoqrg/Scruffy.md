# Scruffy



[Scruffy](/npc/4155) is a level 1 Rat Warrior that spawns in [Qeynos Hills](/zone/4).



## On NPC Spawn

e.self:SetRunning(true);


## Arrive at Waypoint Script

local zoneTime = eq.get_zone_time()["zone_hour"];

if(e.self:GetGrid() == 13 and e.wp > 0 and e.wp < 3) then


e.self:SetRunning(false);

elseif(e.self:GetGrid() == 13 and e.wp == 3) then


e.self:SetRunning(true);


if(zoneTime > 18 or math.random(100) < 20) then



**Scruffy despawns.**

end
