# Spirit of Radir



[Spirit of Radir](/npc/176019) is a level 60 Elemental Warrior that spawns in [The Umbral Plains](/zone/176).





## On NPC Spawn
   **Set a timer** named *depop* for 900 seconds



## Timer(s)

if(e.timer == "depop") then


**Spirit of Radir despawns.**
end



## Combat

if Spirit of Radir enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
