# The skin
## On NPC Spawn

local ex = e.self:GetX();

local ey = e.self:GetY();

local ez = e.self:GetZ();

eq.set_proximity(ex - 30, ex + 30, ey - 30, ey + 30, ez - 30, ez + 30);
function event_enter(e)

e.other:CastToClient():Message(0,"The skin around your eyes tightens in reaction to the vacuum.");