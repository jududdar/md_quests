# A parylyx limb binder


## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**A parylyx limb binder despawns.**
end



## Combat

if  A parylyx limb binder enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
