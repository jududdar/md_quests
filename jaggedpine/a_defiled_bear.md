# a defiled bear


## On NPC Spawn

**Set a timer** named *depop* for 300 seconds


## Timer(s)

if(e.timer == "depop") then


**a defiled bear despawns.**
end



## Combat

if a defiled bear enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
