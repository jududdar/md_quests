# A Rock Studded Champion



[A Rock Studded Champion](/npc/222010) is a level 66 Giant Warrior that spawns in [Plane of Earth](/zone/222).

local INVIS_MAN_ID = 369488;
local GALRONAR_TYPE = 222036;
local GALRONAR_SPAWNID = 369494;
local SPAWNIDS = { 369446, 369447, 369448, 369449 };




## On NPC Spawn

for _, id in ipairs(SPAWNIDS) do


eq.update_spawn_timer(id, 1000);

eq.depop_with_timer(GALRONAR_TYPE);

eq.update_spawn_timer(INVIS_MAN_ID, 1000);


## On NPC Death


if ( not **spawned NPC:**  [A Rock Studded Champion](/npc/222010) ) then 



eq.update_spawn_timer(GALRONAR_SPAWNID, 1000);





local variance = math.random(1, 1440);


local t = (60 * 60 + variance) * 60; 


eq.update_spawn_timer(SPAWNIDS[1], t*1000);
end
