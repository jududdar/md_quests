# a brown bear



[a brown bear](/npc/3028) is a level 3 Bear Warrior that spawns in [Qeynos Hills](/zone/4).

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


if(e.wp == 0 and ZoneTime > 19 and ZoneTime < 8) then



despawntime = 0;



**a brown bear despawns.**

end
