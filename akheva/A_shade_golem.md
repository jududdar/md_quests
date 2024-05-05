# A shade golem



[A shade golem](/npc/179015) is a level 55 Stonegrabber Warrior that spawns in [Akheva Ruins](/zone/179).



## On NPC Spawn

**Set a timer** named *depop* for 75 seconds


## Combat

if A shade golem enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

if(e.timer == "depop") then


**A shade golem despawns.**
end
