# an out of phase spider







## On NPC Spawn

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

eq.set_proximity(xloc - 55, xloc + 55, yloc - 55, yloc + 55); 
function event_enter(e)

>*an out of phase spider phases in!*

**Spawn NPC:**  [\#a phase spider](/npc/123022) at this location.

**an out of phase spider despawns.**
end