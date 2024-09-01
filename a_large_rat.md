# a large rat

[a large rat](/npc/2011) is a level 1 Rat Warrior that spawns in [Qeynos Hills](/zone/4).

Their primary faction is [Giant Rat](/faction/86).local despawntime;





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

if(e.wp == 0 and ZoneTime > 19 and ZoneTime < 8) then

despawntime = 0;

**a large rat despawns.**





