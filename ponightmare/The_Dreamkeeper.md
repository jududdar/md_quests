# The Dreamkeeper



[The Dreamkeeper](/npc/204480) is a level 64 Banshee Shadow Knight that spawns in [Plane of Nightmares](/zone/204).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Combat

if  The Dreamkeeper enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## Timer(s)

if ( e.timer == "depop" ) then


**The Dreamkeeper despawns.**
end
