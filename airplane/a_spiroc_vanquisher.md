# a spiroc vanquisher
local arrive = {};



## On NPC Spawn

local spawnID = e.self:GetSpawnPointID();

arrive[spawnID] = true;


if ( spawnID == 364311 ) then 


**Set a timer** named *caller* for 1 seconds




elseif ( spawnID == 364316 ) then 


**Set a timer** named *expulser* for 1 seconds



elseif ( spawnID == 364322 ) then 


**Set a timer** named *arbiter* for 1 seconds
end



## Signals


if ( e.signal == 1 ) then


**Set a timer** named *arbiter* for 1 seconds




elseif ( e.signal == 2 ) then


**Set a timer** named *caller* for 1 seconds




elseif ( e.signal == 3 ) then


**Set a timer** named *expulser* for 1 seconds
end



## Timer(s)

if ( e.self:IsEngaged() or e.self:Charmed() or not arrive[e.self:GetSpawnPointID()] ) then


return;



if ( e.timer == "arbiter" ) then


if ( not **spawned NPC:**  [a spiroc arbiter](/npc/71008) ) then 



**Spawn NPC from spawn group:** [a spiroc arbiter](/npc/364315) after 1 second(s)





elseif ( e.timer == "caller" ) then


if ( not **spawned NPC:**  [a spiroc caller](/npc/71015) ) then 



**Spawn NPC from spawn group:** [a spiroc caller](/npc/364310) after 1 second(s)




elseif ( e.timer == "expulser" ) then


if ( not **spawned NPC:**  [a spiroc expulser](/npc/71011) ) then 



**Spawn NPC from spawn group:** [a spiroc expulser](/npc/364321) after 1 second(s)




eq.stop_timer(e.timer);


## Combat

if  a spiroc vanquisher enters combat  then


arrive[e.self:GetSpawnPointID()] = false;
end



## Arrive at Waypoint Script

arrive[e.self:GetSpawnPointID()] = true;