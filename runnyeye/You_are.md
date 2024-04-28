# You are
## On NPC Spawn

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

eq.set_proximity(xloc - 25, xloc + 25, yloc - 25, yloc + 25, zloc - 3, zloc + 6);
function event_enter(e)

>*You are not quite sure what a moldmaster is, but you are sure that you don't want to meet it alone, and in the dark.*

**You are despawns.**