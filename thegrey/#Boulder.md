# Boulder



[Boulder](/npc/171008) is a level 55 Stonegrabber Warrior that spawns in [The Grey](/zone/171).



## On NPC Spawn

**Set a timer** named *depop* for 120 seconds


## Timer(s)

if(e.timer == "depop") then


**Boulder despawns.**
end



## Combat

if Boulder enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
