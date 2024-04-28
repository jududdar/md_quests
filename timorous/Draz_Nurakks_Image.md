# Draz Nurakks Image
## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds
## Timer(s)

if(e.timer == "depop") then


**Stop timer** named *depop*


**Draz Nurakks Image despawns.**
end

## Combat

if Draz Nurakks Image enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
