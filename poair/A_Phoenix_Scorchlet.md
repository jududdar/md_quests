# A Phoenix Scorchlet
## On NPC Spawn

**Set a timer** named *depop* for 600 seconds
## Combat

if  A Phoenix Scorchlet enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end

## Timer(s)

if ( e.timer == "depop" and not e.self:Charmed() ) then


**A Phoenix Scorchlet despawns.**
end
