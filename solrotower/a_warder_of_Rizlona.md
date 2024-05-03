# a warder of Rizlona


## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**a warder of Rizlona despawns.**
end



## Combat

if  a warder of Rizlona enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
