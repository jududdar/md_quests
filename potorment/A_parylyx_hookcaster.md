# A parylyx hookcaster

[A parylyx hookcaster](/npc/207300) is a level 60 Arachnid Warrior that spawns in [Torment, the Plane of Pain](/zone/207).

Their primary faction is [Servants of Saryrn](/faction/1624).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds







## Timer(s)

if ( e.timer == "depop" ) then

**A parylyx hookcaster despawns.**









## Combat

if  A parylyx hookcaster enters combat  then

eq.pause_timer("depop");

else

eq.resume_timer("depop");



