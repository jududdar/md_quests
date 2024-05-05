# a warder of Jiva



[a warder of Jiva](/npc/212417) is a level 1 Solusek Ro Guard Warrior that spawns in [Tower of Solusek Ro](/zone/212).



## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**a warder of Jiva despawns.**
end



## Combat

if  a warder of Jiva enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
