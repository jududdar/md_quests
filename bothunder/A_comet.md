# A comet


## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**A comet despawns.**
end



## Combat

if  A comet enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
