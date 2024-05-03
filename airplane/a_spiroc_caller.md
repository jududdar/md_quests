# a spiroc caller
local arrive = false;



## On NPC Death

**Signaled to:**  [a spiroc vanquisher](/npc/71009)


## On NPC Spawn

**Set a timer** named *walker* for 1 seconds

arrive = true;


## Signals

if ( e.signal == 1 ) then


**Set a timer** named *walker* for 1 seconds
end



## Timer(s)

if ( not arrive or e.self:IsEngaged() or e.self:Charmed() ) then


return;



if ( not **spawned NPC:**  [a spiroc walker](/npc/71014) ) then 


**Spawn NPC from spawn group:** [a spiroc walker](/npc/364309) after 1 second(s)

eq.stop_timer(e.timer);


## Combat

if  a spiroc caller enters combat  then


arrive = false;
end



## Arrive at Waypoint Script

arrive = true;