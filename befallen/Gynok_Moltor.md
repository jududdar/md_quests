# Gynok Moltor



[Gynok Moltor](/npc/36103) is a level 21 Zombie Warrior that spawns in [Befallen](/zone/36).



## Arrive at Waypoint Script

if(e.wp == 55 or e.wp == 117) then


e.self:SetRunning(true);

elseif(e.wp == 82) then


e.self:SetRunning(false);
end