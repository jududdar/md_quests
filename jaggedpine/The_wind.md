# The wind


## On NPC Spawn

local ex = e.self:GetX();

local ey = e.self:GetY();

local ez = e.self:GetZ();

eq.set_proximity(ex - 60, ex + 60, ey - 60, ey + 60, ez - 30, ez + 30);
function event_enter(e)

>*The wind coalesces into a corporeal form.*

**Spawn NPC:**  [a dryad](/npc/181013) at this location.

**The wind despawns.**