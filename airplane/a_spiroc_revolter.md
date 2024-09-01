# a spiroc revolter

[a spiroc revolter](/npc/71010) is a level 52 Aviak Ranger that spawns in [Plane of Sky](/zone/71).

Their primary faction is [KOS](/faction/5017).

local arrive = false;





## On NPC Death

**Signaled to:**  [a spiroc expulser](/npc/71011)







## On NPC Spawn

**Set a timer** named *guardian* for 1 seconds

arrive = true;







## Signals

if ( e.signal == 1 ) then

**Set a timer** named *guardian* for 1 seconds









## Timer(s)

if ( not arrive or e.self:IsEngaged() or e.self:Charmed() ) then

return;





if ( not **spawned NPC:**  [The Spiroc Guardian](/npc/71013) ) then 

**Spawn NPC from spawn group:**  Unknown NPC with id: 364319. after 1 second(s)



eq.stop_timer(e.timer);







## Combat

if  a spiroc revolter enters combat  then

arrive = false;









## Arrive at Waypoint Script

arrive = true;

