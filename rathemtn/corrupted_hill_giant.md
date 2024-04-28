# corrupted hill giant
## On NPC Spawn

**Set a timer** named *depop* for 600 seconds
## Timer(s)

**corrupted hill giant despawns.**
## Combat

if corrupted hill giant enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
