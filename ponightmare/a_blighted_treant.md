# a blighted treant
## On NPC Spawn

**Set a timer** named *depop* for 100 seconds
## Combat

if  a blighted treant enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end

## Timer(s)

if ( e.timer == "depop" ) then


**a blighted treant despawns.**
end
