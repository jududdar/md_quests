# an angry pansy

[an angry pansy](/npc/126000) is a level 48 Man-Eating Plant Warrior that spawns in [Plane of Mischief](/zone/126).

Their primary faction is [KOS](/faction/5017).

## On NPC Spawn

**Set a timer** named *depop* for 120 seconds







## Combat

if an angry pansy enters combat  then

if(not eq.is_paused_timer("depop")) then

eq.pause_timer("depop");



else

eq.resume_timer("depop");









## Timer(s)

**an angry pansy despawns.**

