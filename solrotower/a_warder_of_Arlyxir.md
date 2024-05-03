# a warder of Arlyxir


## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**a warder of Arlyxir despawns.**
end



## Combat

if  a warder of Arlyxir enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
