# a haunting voice







## On NPC Spawn

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

eq.set_proximity(xloc - 25, xloc + 25, yloc - 25, yloc + 25, zloc - 3, zloc + 6);
function event_enter(e)

>**a haunting voice says:** Please, you must turn back. They no longer recognize, they no longer know.

**a haunting voice despawns.**