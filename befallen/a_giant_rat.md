# a giant rat

[a giant rat](/npc/4009) is a level 2 Rat Warrior that spawns in [Befallen](/zone/36).

Their primary faction is [Giant Rat](/faction/86).

## Arrive at Waypoint Script
if(e.wp == 55 or e.wp == 117) then
e.self:SetRunning(true);
elseif(e.wp == 82) then
e.self:SetRunning(false);

