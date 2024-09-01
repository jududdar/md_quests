# a spiroc arbiter

[a spiroc arbiter](/npc/71008) is a level 52 Aviak Druid that spawns in [Plane of Sky (Instanced)](/zone/1071).

Their primary faction is [KOS](/faction/5017).

local arrive = false;





## On NPC Death

**Signaled to:**  [a spiroc vanquisher](/npc/71022)







## On NPC Spawn

**Set a timer** named *banisher* for 1 seconds

arrive = true;







## Signals

if ( e.signal == 1 ) then

**Set a timer** named *banisher* for 1 seconds









## Timer(s)

if ( not arrive or e.self:IsEngaged() or e.self:Charmed() ) then

return;





if ( not **spawned NPC:**  [a spiroc banisher](/npc/71007) ) then 

**Spawn NPC from spawn group:**  Unknown NPC with id: 364314. after 1 second(s)



eq.stop_timer(e.timer);







## Combat

if  a spiroc arbiter enters combat  then

arrive = false;









## Arrive at Waypoint Script

arrive = true;

