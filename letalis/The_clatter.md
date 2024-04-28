# The clatter
## On NPC Spawn

local ex = e.self:GetX();

local ey = e.self:GetY();

local ez = e.self:GetZ();

eq.set_proximity(ex - 30, ex + 30, ey - 30, ey + 30, ez - 30, ez + 30);
function event_enter(e)

>*The clatter of loose gravel attracts your attention. Is something up there?*

**The clatter despawns.**