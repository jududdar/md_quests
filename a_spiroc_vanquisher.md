# a spiroc vanquisher

[a spiroc vanquisher](/npc/71009) is a level 58 Aviak Warrior that spawns in [Plane of Sky (Instanced)](/zone/1071).

Their primary faction is [KOS](/faction/5017).local arrive = {};





## On NPC Spawn

local spawnID = e.self:GetSpawnPointID();

arrive[spawnID] = true;



if ( spawnID == 364311 ) then 

**Set a timer** named *caller* for 1 seconds



elseif ( spawnID == 364316 ) then 

**Set a timer** named *expulser* for 1 seconds



elseif ( spawnID == 364322 ) then 

**Set a timer** named *arbiter* for 1 seconds









## Signals



if ( e.signal == 1 ) then

**Set a timer** named *arbiter* for 1 seconds



elseif ( e.signal == 2 ) then

**Set a timer** named *caller* for 1 seconds



elseif ( e.signal == 3 ) then

**Set a timer** named *expulser* for 1 seconds









## Timer(s)

if ( e.self:IsEngaged() or e.self:Charmed() or not arrive[e.self:GetSpawnPointID()] ) then

return;





local elist = eq.get_entity_list();



if ( e.timer == "arbiter" ) then

if ( not elist:IsMobSpawnedByNpcTypeID(71008) ) then 

**Spawn NPC from spawn group:**  Unknown NPC with id: 364315. after 1 second(s)





elseif ( e.timer == "caller" ) then

if ( not elist:IsMobSpawnedByNpcTypeID(71015) ) then 

**Spawn NPC from spawn group:**  Unknown NPC with id: 364310. after 1 second(s)





elseif ( e.timer == "expulser" ) then

if ( not elist:IsMobSpawnedByNpcTypeID(71011) ) then 

**Spawn NPC from spawn group:**  Unknown NPC with id: 364321. after 1 second(s)







eq.stop_timer(e.timer);







## Combat

if  a spiroc vanquisher enters combat  then

arrive[e.self:GetSpawnPointID()] = false;









## Arrive at Waypoint Script

arrive[e.self:GetSpawnPointID()] = true;

