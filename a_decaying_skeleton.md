# a decaying skeleton

[a decaying skeleton](/npc/2104) is a level 1 Skeleton Warrior that spawns in [Qeynos Hills](/zone/4).

Their primary faction is [Decaying Skeleton](/faction/5071).local despawntime;





## On NPC Spawn

if(e.self:GetSpawnPointID() == 365105 or e.self:GetSpawnPointID() == 365106) then

despawntime = 0;

**Set a timer** named *depop* for 8640 seconds









## Timer(s)

if(e.timer == "depop") then

**Stop timer** named *depop*

despawntime = 1;









## Arrive at Waypoint Script

local ZoneTime = eq.get_zone_time()["zone_hour"];

if(e.self:GetGrid() == 26 and despawntime == 1) then

if(e.wp == 0 and ZoneTime > 7 and ZoneTime < 20) then

despawntime = 0;

**a decaying skeleton despawns.**





