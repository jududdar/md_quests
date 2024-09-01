# a dryad

[a dryad](/npc/181013) is a level 40 Dryad Druid that spawns in [Jaggedpine Forest](/zone/181).

Their primary faction is [Dryads of the Grove](/faction/1603).

## On NPC Spawn
**Set a timer** named *depop* for 120 seconds




## Timer(s)
if(e.timer == "depop") then
**a dryad despawns.**





## Combat
if a dryad enters combat  then
if(not eq.is_paused_timer("depop")) then
eq.pause_timer("depop");

else
eq.resume_timer("depop");

