# a molded skeleton


## On NPC Spawn

**Set a timer** named *depop* for 120 seconds


## Timer(s)

if(e.timer == "depop") then


**a molded skeleton despawns.**
end



## Combat

if a molded skeleton enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
