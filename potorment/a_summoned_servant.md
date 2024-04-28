# a summoned servant
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
