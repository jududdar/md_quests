# a twisted spirit

[a twisted spirit](/npc/207308) is a level 59 Blood Raven Warrior that spawns in [Torment, the Plane of Pain](/zone/207).

Their primary faction is [Servants of Saryrn](/faction/1624).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds







## Timer(s)

if ( e.timer == "depop" ) then

**a twisted spirit despawns.**









## Combat

if  a twisted spirit enters combat  then

eq.pause_timer("depop");

else

eq.resume_timer("depop");



