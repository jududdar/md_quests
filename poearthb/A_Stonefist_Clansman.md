# A Stonefist Clansman



[A Stonefist Clansman](/npc/222009) is a level 66 Giant Warrior that spawns in [Plane of Earth](/zone/222).

local INVIS_MAN_ID = 369487;
local BIRAK_TYPE = 222035;
local BIRAK_SPAWNID = 369493;
local SPAWNIDS = { 369442, 369443, 369444, 369445 };




## On NPC Spawn

for _, id in ipairs(SPAWNIDS) do


eq.update_spawn_timer(id, 1000);

eq.depop_with_timer(BIRAK_TYPE);

eq.update_spawn_timer(INVIS_MAN_ID, 1000);


## On NPC Death


if ( not **spawned NPC:**  [A Stonefist Clansman](/npc/222009) ) then 



eq.update_spawn_timer(BIRAK_SPAWNID, 1000);





local variance = math.random(1, 1440);


local t = (60 * 60 + variance) * 60; 


eq.update_spawn_timer(SPAWNIDS[1], t*1000);
end
