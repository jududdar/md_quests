# A firestorm


## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**A firestorm despawns.**
end



## Combat

if  A firestorm enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
