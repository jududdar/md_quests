# Varsoon



[Varsoon](/npc/4171) is a level 25 Human Necromancer that spawns in [Qeynos Hills](/zone/4).

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



**Varsoon despawns.**

end



## Dialog

**You say:** `hail`



>**Varsoon says:** How dare you address me thus?!  Your ignorance shall bring your doom!


**Varsoon attacks you.**
end



## On NPC Death

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

local hloc = e.self:GetHeading();


eq.spawn2(4190,26,0,xloc,yloc,zloc,hloc); 