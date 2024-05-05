# a summoned servant



[a summoned servant](/npc/207306) is a level 59 Blood Raven Warrior that spawns in [Torment, the Plane of Pain](/zone/207).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**a summoned servant despawns.**
end



## Combat

if  a summoned servant enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
