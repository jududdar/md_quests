# an abhorrent hatchling



[an abhorrent hatchling](/npc/204475) is a level 52 Arachnid Warrior that spawns in [Plane of Nightmares](/zone/204).



## On NPC Spawn

**Set a timer** named *depop* for 300 seconds


## Combat

if  an abhorrent hatchling enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## Timer(s)

if ( e.timer == "depop" ) then


**an abhorrent hatchling despawns.**
end
