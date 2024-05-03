# The Dreamkeeper


## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Combat

if  The Dreamkeeper enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## Timer(s)

if ( e.timer == "depop" ) then


**The Dreamkeeper despawns.**
end
