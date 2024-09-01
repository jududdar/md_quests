# a boulderling

[a boulderling](/npc/171004) is a level 38 Stonegrabber Warrior that spawns in [The Grey](/zone/171).

Their primary faction is [KOS](/faction/5017).

## On NPC Spawn
**Set a timer** named *depop* for 120 seconds




## Timer(s)
if(e.timer == "depop") then
**a boulderling despawns.**





## Combat
if a boulderling enters combat  then
if(not eq.is_paused_timer("depop")) then
eq.pause_timer("depop");

else
eq.resume_timer("depop");

