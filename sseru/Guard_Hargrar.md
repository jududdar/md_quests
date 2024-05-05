# Guard Hargrar



[Guard Hargrar](/npc/159001) is a level 50 Barbarian Warrior that spawns in [Sanctus Seru](/zone/159).





## On NPC Spawn

**Set a timer** named *depop* for 300 seconds


## Combat

if Guard Hargrar enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

if(e.timer == "depop") then


**Guard Hargrar despawns.**
end