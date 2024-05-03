# a putrid skeleton
local despawntime;



## On NPC Spawn

if(e.self:GetSpawnPointID() == 365105 or e.self:GetSpawnPointID() == 365106) then


despawntime = 0;


**Set a timer** named *depop* for 8640 seconds
end



## Timer(s)

if(e.timer == "depop") then


**Stop timer** named *depop*


despawntime = 1;
end



## Arrive at Waypoint Script

local ZoneTime = eq.get_zone_time()["zone_hour"];

if(e.self:GetGrid() == 26 and despawntime == 1) then


if(e.wp == 0 and ZoneTime > 7 and ZoneTime < 20) then



despawntime = 0;



**a putrid skeleton despawns.**

end