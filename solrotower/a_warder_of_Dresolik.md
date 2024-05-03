# a warder of Dresolik


## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**a warder of Dresolik despawns.**
end



## Combat

if  a warder of Dresolik enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
