# A Lesser Spire Spirit



[A Lesser Spire Spirit](/npc/169002) is a level 33 Shade Necromancer that spawns in [Mons Letalis](/zone/169).



## On NPC Spawn

**Set a timer** named *depop* for 120 seconds


## Timer(s)

if(e.timer == "depop") then


**A Lesser Spire Spirit despawns.**
end



## Combat

if A Lesser Spire Spirit enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
