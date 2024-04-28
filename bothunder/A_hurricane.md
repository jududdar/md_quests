# A hurricane
## On NPC Spawn

**Set a timer** named *depop* for 600 seconds
## Timer(s)

if ( e.timer == "depop" ) then


**A hurricane despawns.**
end

## Combat

if  A hurricane enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
