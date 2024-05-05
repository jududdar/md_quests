# a spiroc banisher



[a spiroc banisher](/npc/71007) is a level 52 Aviak Ranger that spawns in [Plane of Sky](/zone/71).

local arrive = false;



## On NPC Death

**Signaled to:**  [a spiroc arbiter](/npc/71008)


## On NPC Spawn

**Set a timer** named *guardian* for 1 seconds

arrive = true;


## Signals

if ( e.signal == 1 ) then


**Set a timer** named *guardian* for 1 seconds
end



## Timer(s)

if ( not arrive or e.self:IsEngaged() or e.self:Charmed() ) then


return;



if ( not **spawned NPC:**  [The Spiroc Guardian](/npc/71013) ) then 


**Spawn NPC from spawn group:** [The Spiroc Guardian](/npc/364319) after 1 second(s)

eq.stop_timer(e.timer);


## Combat

if  a spiroc banisher enters combat  then


arrive = false;
end



## Arrive at Waypoint Script

arrive = true;