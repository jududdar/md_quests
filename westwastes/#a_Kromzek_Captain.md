# a Kromzek Captain
## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds
## Combat

if a Kromzek Captain enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end

## Timer(s)

**a Kromzek Captain despawns.**
end