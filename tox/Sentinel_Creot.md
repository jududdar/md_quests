# Sentinel Creot



[Sentinel Creot](/npc/38053) is a level 30 Erudite Paladin that spawns in [Toxxulia Forest](/zone/38).



## Arrive at Waypoint Script

if((e.wp == 1) or (e.wp == 3)) then


>**Sentinel Creot says:** Hail citizens.  Sentinel Creot of the High Guard is on watch.

elseif(e.wp == 1) then


e.self:SetRunning(true);

elseif(e.wp == 2) then


e.self:SetRunning(false);
end





