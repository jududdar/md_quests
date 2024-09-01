# a pretty ugly pansy

[a pretty ugly pansy](/npc/126001) is a level 48 Man-Eating Plant Warrior that spawns in [Plane of Mischief](/zone/126).

Their primary faction is [KOS](/faction/5017).

## On NPC Spawn

**Set a timer** named *depop* for 120 seconds







## Combat

if a pretty ugly pansy enters combat  then

if(not eq.is_paused_timer("depop")) then

eq.pause_timer("depop");



else

eq.resume_timer("depop");









## Timer(s)

**a pretty ugly pansy despawns.**

