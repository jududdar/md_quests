# corrupted hill giant



[corrupted hill giant](/npc/50322) is a level 40 Giant Warrior that spawns in [Rathe Mountains](/zone/50).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Timer(s)

**corrupted hill giant despawns.**


## Combat

if corrupted hill giant enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
