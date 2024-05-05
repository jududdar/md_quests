# A parylyx hatchling



[A parylyx hatchling](/npc/207299) is a level 57 Arachnid Warrior that spawns in [Torment, the Plane of Pain](/zone/207).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**A parylyx hatchling despawns.**
end



## Combat

if  A parylyx hatchling enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
