# You step
## On NPC Spawn

local ex = e.self:GetX();

local ey = e.self:GetY();

local ez = e.self:GetZ();

eq.set_proximity(ex - 30, ex + 30, ey - 30, ey + 30, ez - 30, ez + 30);
function event_enter(e)

>*You step on a fresh grave and the soil around you springs to life!*

**Spawn NPC:** eq.ChooseRandom( [a muddy corpse](/npc/160006), [a ghastly apparition](/npc/160007), [a molded skeleton](/npc/160095), [a reanimated corpse](/npc/160096)) at this location.

**You step despawns.**