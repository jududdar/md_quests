# A storm cloud
## On NPC Spawn

**Set a timer** named *depop* for 600 seconds
## Timer(s)

if ( e.timer == "depop" ) then


**A storm cloud despawns.**
end

## Combat

if  A storm cloud enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
