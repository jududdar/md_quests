# a reanimated Vah Shir



[a reanimated Vah Shir](/npc/160172) is a level 39 Vah Shir Skeleton Warrior that spawns in [Katta Castellum](/zone/160).





## On NPC Spawn

**Set a timer** named *depop* for 300 seconds


## Timer(s)

if(e.timer == "depop") then


**a reanimated Vah Shir despawns.**
end



## Combat

if a reanimated Vah Shir enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end