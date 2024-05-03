# A parylyx widow


## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**A parylyx widow despawns.**
end



## Combat

if  A parylyx widow enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
