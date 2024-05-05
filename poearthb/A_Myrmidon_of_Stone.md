# A Myrmidon of Stone



[A Myrmidon of Stone](/npc/222008) is a level 66 Giant Warrior that spawns in [Plane of Earth](/zone/222).

local INVIS_MAN_ID = 369489;
local AWISANO_TYPE = 222037;
local AWISANO_SPAWNID = 369492;
local SPAWNIDS = { 369438, 369439, 369440, 369441 };




## On NPC Spawn

for _, id in ipairs(SPAWNIDS) do


eq.update_spawn_timer(id, 1000);

eq.depop_with_timer(AWISANO_TYPE);

eq.update_spawn_timer(INVIS_MAN_ID, 1000);


## On NPC Death


if ( not **spawned NPC:**  [A Myrmidon of Stone](/npc/222008) ) then 



eq.update_spawn_timer(AWISANO_SPAWNID, 1000);





local variance = math.random(1, 1440);


local t = (60 * 60 + variance) * 60; 


eq.update_spawn_timer(SPAWNIDS[1], t*1000);
end
