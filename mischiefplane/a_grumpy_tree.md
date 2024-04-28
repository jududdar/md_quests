# a grumpy tree
local pansy = 0;

## On NPC Spawn

local ex = e.self:GetX();

local ey = e.self:GetY();

local ez = e.self:GetZ();

eq.set_proximity(ex - 65, ex + 65, ey - 65, ey + 65, ez - 10, ez + 20);
function event_enter(e)

>*a grumpy tree throws a bunch of pansies at you.*

pansy = math.random(1,5);

if(pansy == 5) then


**Spawn NPC:** eq.ChooseRandom( [a dandy pansy](/npc/126002), [a pretty ugly pansy](/npc/126001), [a puny pansy](/npc/126003), [an angry pansy](/npc/126000)) at this location.


**Spawn NPC:** eq.ChooseRandom( [a dandy pansy](/npc/126002), [a pretty ugly pansy](/npc/126001), [a puny pansy](/npc/126003), [an angry pansy](/npc/126000)) at this location.


**Spawn NPC:** eq.ChooseRandom( [a dandy pansy](/npc/126002), [a pretty ugly pansy](/npc/126001), [a puny pansy](/npc/126003), [an angry pansy](/npc/126000)) at this location.

elseif(pansy == 3 or pansy == 4) then


**Spawn NPC:** eq.ChooseRandom( [a dandy pansy](/npc/126002), [a pretty ugly pansy](/npc/126001), [a puny pansy](/npc/126003), [an angry pansy](/npc/126000)) at this location.


**Spawn NPC:** eq.ChooseRandom( [a dandy pansy](/npc/126002), [a pretty ugly pansy](/npc/126001), [a puny pansy](/npc/126003), [an angry pansy](/npc/126000)) at this location.

else


**Spawn NPC:** eq.ChooseRandom( [a dandy pansy](/npc/126002), [a pretty ugly pansy](/npc/126001), [a puny pansy](/npc/126003), [an angry pansy](/npc/126000)) at this location.

**a grumpy tree despawns.**