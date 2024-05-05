# a swarming beetle



[a swarming beetle](/npc/123024) is a level 49 Beetle Warrior that spawns in [Dragon Necropolis](/zone/123).



## On NPC Spawn

**Set a timer** named *depop* for 120 seconds


## Combat

if a swarming beetle enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

**a swarming beetle despawns.**
end