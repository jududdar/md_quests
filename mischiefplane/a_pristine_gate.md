# a pristine gate


## On NPC Spawn

local ex = e.self:GetX();

local ey = e.self:GetY();

local ez = e.self:GetZ();

eq.set_proximity(ex - 65, ex + 65, ey - 65, ey + 65, ez - 10, ez + 20);
function event_enter(e)

**a pristine gate casts:** [Nulling Void](/spell/2098) on target.