# a fish



[a fish](/npc/3002) is a level 1 Fish Warrior that spawns in [Kael Drakkel](/zone/113).



## On NPC Spawn

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

eq.set_proximity(xloc - 45, xloc + 45, yloc - 45, yloc + 45, zloc - 3, zloc + 6);
function event_enter(e)

>*a fish nearly jumps onto the ice.*

**a fish despawns.**