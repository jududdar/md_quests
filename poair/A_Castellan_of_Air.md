# A Castellan of Air
local CONTROLLER_TYPE = 215419; 
local INLOKHER_TYPE = 215409; 

## On NPC Death


eq.signal(CONTROLLER_TYPE, 1);

**Signaled to:**  [\#Constable Alranderisan](/npc/215383)

**Signaled to:**  [\#Constable Belecohen](/npc/215384)

**Signaled to:**  [\#Constable Ferabalen](/npc/215385)


local roll = math.random(100);



if ( roll < 6 and not eq.get_entity_list():IsMobSpawnedByNpcTypeID(INLOKHER_TYPE) ) then


eq.spawn2(INLOKHER_TYPE, 0, 0, e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0);



roll = math.random(1, 4);



for i = 1, roll do


**Spawn NPC:**  [A Vengeful Airspirit](/npc/215413) at this location.
end
