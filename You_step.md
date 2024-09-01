

## On NPC Spawn

local ex = e.self:GetX();

local ey = e.self:GetY();

local ez = e.self:GetZ();

eq.set_proximity(ex - 30, ex + 30, ey - 30, ey + 30, ez - 30, ez + 30);





function event_enter(e)

>*You step on a fresh grave and the soil around you springs to life!*

**Spawn NPC:**  Unknown NPC with id: .eq.ChooseRandom(160006,160007,160095,160096) at this location.

**You step despawns.**

