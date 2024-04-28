# a twisted spirit
## On NPC Spawn

**Set a timer** named *depop* for 600 seconds
## Timer(s)

if ( e.timer == "depop" ) then


**a twisted spirit despawns.**
end

## Combat

if  a twisted spirit enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
