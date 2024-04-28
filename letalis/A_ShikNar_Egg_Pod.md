# A ShikNar Egg Pod
## On NPC Spawn

local ex = e.self:GetX();

local ey = e.self:GetY();

local ez = e.self:GetZ();

eq.set_proximity(ex - 30, ex + 30, ey - 30, ey + 30, ez - 30, ez + 30);
function event_enter(e)

>*A ShikNar Egg Pod cracks open, releasing hungry hatchlings!*

rand = math.random(100);

if(rand < 30) then


**Spawn NPC:**  [A ShikNar Hatchling](/npc/169001) at this location.

elseif(rand < 60) then


**Spawn NPC:**  [A ShikNar Hatchling](/npc/169001) at this location.


**Spawn NPC:**  [A ShikNar Hatchling](/npc/169001) at this location.

else


**Spawn NPC:**  [A ShikNar Hatchling](/npc/169001) at this location.


**Spawn NPC:**  [A ShikNar Hatchling](/npc/169001) at this location.


**Spawn NPC:**  [A ShikNar Hatchling](/npc/169001) at this location.

**A ShikNar Egg Pod despawns.**