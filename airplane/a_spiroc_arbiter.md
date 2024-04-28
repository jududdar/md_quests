# a spiroc arbiter
local arrive = false;

## On NPC Death

**Signaled to:**  [a spiroc vanquisher](/npc/71022)
## On NPC Spawn

**Set a timer** named *banisher* for 1 seconds

arrive = true;
## Signals

if ( e.signal == 1 ) then


**Set a timer** named *banisher* for 1 seconds
end

## Timer(s)

if ( not arrive or e.self:IsEngaged() or e.self:Charmed() ) then


return;



if ( not **spawned NPC:**  [a spiroc banisher](/npc/71007) ) then 


**Spawn NPC from spawn group:** [a spiroc banisher](/npc/364314) after 1 second(s)

eq.stop_timer(e.timer);
## Combat

if  a spiroc arbiter enters combat  then


arrive = false;
end

## Arrive at Waypoint Script

arrive = true;