# The Avatar of War
## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds
## Timer(s)

if(e.timer == "depop") then


**The Avatar of War despawns.**
end

## Combat

if The Avatar of War enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end

## On NPC Death

eq.delete_global("Avatar");