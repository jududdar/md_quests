# an arena tiger


## On NPC Spawn

**Set a timer** named *depop* for 300 seconds


## Combat

if an arena tiger enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

if(e.timer == "depop") then


**an arena tiger despawns.**
end