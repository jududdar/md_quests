# A parylyx painweaver
## On NPC Spawn

**Set a timer** named *depop* for 600 seconds
## Timer(s)

if ( e.timer == "depop" ) then


**A parylyx painweaver despawns.**
end

## Combat

if  A parylyx painweaver enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
