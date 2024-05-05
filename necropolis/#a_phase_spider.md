# a phase spider



[a phase spider](/npc/123022) is a level 47 Spider Warrior that spawns in [Dragon Necropolis](/zone/123).



## On NPC Spawn

**Set a timer** named *depop* for 5400 seconds


## Combat
 
if a phase spider enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
 


## Timer(s)

**a phase spider despawns.**
end