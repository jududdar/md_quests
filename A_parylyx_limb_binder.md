# A parylyx limb binder

[A parylyx limb binder](/npc/207301) is a level 59 Arachnid Warrior that spawns in [Torment, the Plane of Pain](/zone/207).

Their primary faction is [Servants of Saryrn](/faction/1624).

## On NPC Spawn

**Set a timer** named *depop* for 600 seconds







## Timer(s)

if ( e.timer == "depop" ) then

**A parylyx limb binder despawns.**









## Combat

if  A parylyx limb binder enters combat  then

eq.pause_timer("depop");

else

eq.resume_timer("depop");



