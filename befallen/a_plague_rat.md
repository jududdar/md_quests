# a plague rat



[a plague rat](/npc/36022) is a level 4 Rat Warrior that spawns in [Befallen](/zone/36).



## Arrive at Waypoint Script

if(e.wp == 55 or e.wp == 117) then


e.self:SetRunning(true);

elseif(e.wp == 82) then


e.self:SetRunning(false);
end