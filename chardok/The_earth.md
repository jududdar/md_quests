# The earth
## On NPC Spawn

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

eq.set_proximity(xloc - 45, xloc + 45, yloc - 45, yloc + 45, zloc - 3, zloc + 6);
function event_enter(e)

>*The earth at your feet erupts!*

**Spawn NPC:** eq.ChooseRandom( [a Reanimated Champion ](/npc/103158), [a Reanimated Champion ](/npc/103158), [a Reanimated Berserker ](/npc/103159)) at this location.

**The earth despawns.**