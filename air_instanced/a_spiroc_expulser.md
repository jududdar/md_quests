# a spiroc expulser

[a spiroc expulser](/npc/71011) is a level 52 Aviak Druid that spawns in [Plane of Sky (Instanced)](/zone/1071).

Their primary faction is [KOS](/faction/5017).

local arrive = false;





## On NPC Death

**Signaled to:**  [a spiroc vanquisher](/npc/71020)







## On NPC Spawn

**Set a timer** named *revolter* for 1 seconds

arrive = true;







## Signals

if ( e.signal == 1 ) then

**Set a timer** named *revolter* for 1 seconds









## Timer(s)

if ( not arrive or e.self:IsEngaged() or e.self:Charmed() ) then

return;





if ( not **spawned NPC:**  [a spiroc revolter](/npc/71010) ) then 

**Spawn NPC from spawn group:**  Unknown NPC with id: 364320. after 1 second(s)



eq.stop_timer(e.timer);







## Combat

if  a spiroc expulser enters combat  then

arrive = false;









## Arrive at Waypoint Script

arrive = true;

