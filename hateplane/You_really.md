# You really





function event_spawn(event)

local xloc = event.self:GetX();

local yloc = event.self:GetY();

local zloc = event.self:GetZ();

eq.set_proximity(xloc - 25, xloc + 25, yloc - 25, yloc + 25, zloc - 25, zloc + 25);
function event_enter(event)

event.self:Emote("hate this place.");

**You really despawns.**