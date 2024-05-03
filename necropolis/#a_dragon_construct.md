# a dragon construct


## On NPC Spawn

**Set a timer** named *depop* for 300 seconds


## Combat

if a dragon construct enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

**a dragon construct despawns.**
end