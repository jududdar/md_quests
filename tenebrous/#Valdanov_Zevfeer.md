# Valdanov Zevfeer
## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds
## Timer(s)

if(e.timer == "depop") then


**Valdanov Zevfeer despawns.**
end

## Combat

if Valdanov Zevfeer enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
