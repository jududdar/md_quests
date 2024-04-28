# a rapacious hatchling
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Combat

if  a rapacious hatchling enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end

## Timer(s)

if ( e.timer == "depop" ) then


**a rapacious hatchling despawns.**
end
