# a pile of mold
## On NPC Spawn

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

eq.set_proximity(xloc - 25, xloc + 25, yloc - 25, yloc + 25, zloc - 3, zloc + 6);
function event_enter(e)

>*a pile of mold erupts in a cloud of spores!*

**Spawn NPC:**  [a sporeling](/npc/11000) at this location.

**a pile of mold despawns.**