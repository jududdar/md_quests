# a blood starved wolf
## On NPC Spawn

**Set a timer** named *depop* for 95 seconds
## Timer(s)

**a blood starved wolf despawns.**
## Combat

if a blood starved wolf enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end