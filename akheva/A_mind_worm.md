# A mind worm
## On NPC Spawn

**Set a timer** named *depop* for 75 seconds
## Combat

if A mind worm enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end

## Timer(s)

if(e.timer == "depop") then


**A mind worm despawns.**
end
