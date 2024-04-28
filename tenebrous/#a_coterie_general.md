# a coterie general
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Timer(s)

if(e.timer == "depop") then


**a coterie general despawns.**
end

## Combat

if a coterie general enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end