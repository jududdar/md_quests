# a Runnyeye conscript

[a Runnyeye conscript](/npc/11028) is a level 4 Goblin Wizard that spawns in [Runnyeye](/zone/11).

Their primary faction is [Clan Runnyeye](/faction/225).

## Arrive at Waypoint Script
if(e.wp == 128) then
e.self:SetRunning(true);
elseif(e.wp == 160) then
e.self:SetRunning(false);

