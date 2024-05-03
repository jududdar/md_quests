# Hollish Tnoops


## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds

e.self:SetRunning(true);


## Combat

if Hollish Tnoops enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

**Hollish Tnoops despawns.**
end