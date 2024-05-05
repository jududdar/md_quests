# An Arachnae Maleveler



[An Arachnae Maleveler](/npc/205157) is a level 60 Arachnid Warrior that spawns in [Plane of Disease](/zone/205).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Combat

if  An Arachnae Maleveler enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## Timer(s)

if ( e.timer == "depop" ) then


**An Arachnae Maleveler despawns.**
end
