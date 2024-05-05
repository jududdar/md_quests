# A parylyx painweaver



[A parylyx painweaver](/npc/207302) is a level 58 Arachnid Warrior that spawns in [Torment, the Plane of Pain](/zone/207).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**A parylyx painweaver despawns.**
end



## Combat

if  A parylyx painweaver enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
