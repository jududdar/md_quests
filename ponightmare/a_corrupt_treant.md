# a corrupt treant



[a corrupt treant](/npc/204460) is a level 55 Treant Warrior that spawns in [Plane of Nightmares](/zone/204).



## On NPC Spawn

**Set a timer** named *depop* for 100 seconds


## Combat

if  a corrupt treant enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## Timer(s)

if ( e.timer == "depop" ) then


**a corrupt treant despawns.**
end
