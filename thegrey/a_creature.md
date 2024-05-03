# a creature




## On NPC Spawn

local ex = e.self:GetX();

local ey = e.self:GetY();

local ez = e.self:GetZ();

eq.set_proximity(ex - 65, ex + 65, ey - 65, ey + 65, ez - 60, ez + 60);
function event_enter(e)

>*a creature of living stone leaps out at you from amongst the rocks!*

creature = math.random(100);

if(creature < 30) then


**Spawn NPC:**  [a boulderling](/npc/171004) at this location.


**Spawn NPC:**  [a boulderling](/npc/171004) at this location.


**Spawn NPC:**  [a boulderling](/npc/171004) at this location.

elseif(creature < 60) then


**Spawn NPC:**  [a boulder fiend](/npc/171006) at this location.


**Spawn NPC:**  [a boulder fiend](/npc/171006) at this location.

elseif(creature < 80) then


**Spawn NPC:**  [a stone beast](/npc/171007) at this location.

elseif(creature < 90) then


**Spawn NPC:**  [\#Boulder](/npc/171008) at this location.

else


**Spawn NPC:**  [\#Stonehand](/npc/171009) at this location.

**a creature despawns.**