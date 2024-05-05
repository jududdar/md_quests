# A shadow reaver



[A shadow reaver](/npc/179346) is a level 53 Shade Warrior that spawns in [Akheva Ruins](/zone/179).



## On NPC Spawn

**Set a timer** named *depop* for 75 seconds


## Combat

if A shadow reaver enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

if(e.timer == "depop") then


**A shadow reaver despawns.**
end
