# TerrorSpawner


## On NPC Spawn

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

eq.set_proximity(xloc - 45, xloc + 45, yloc - 45, yloc + 45, zloc - 3, zloc + 6);
function event_enter(e)

**Spawn NPC:** eq.ChooseRandom( [a crystal shard](/npc/112076), [a crystal shard](/npc/112076), [a crystal shard](/npc/112076), [a large crystal shard](/npc/112077)) at this location.

**TerrorSpawner despawns.**