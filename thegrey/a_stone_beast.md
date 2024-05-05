# a stone beast



[a stone beast](/npc/171007) is a level 48 Stonegrabber Warrior that spawns in [The Grey](/zone/171).



## On NPC Spawn

**Set a timer** named *depop* for 120 seconds


## Timer(s)

if(e.timer == "depop") then


**a stone beast despawns.**
end



## Combat

if a stone beast enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
