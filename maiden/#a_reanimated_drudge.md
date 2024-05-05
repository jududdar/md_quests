# a reanimated drudge



[a reanimated drudge](/npc/173005) is a level 52 Skeleton Warrior that spawns in [The Maiden's Eye](/zone/173).



## On NPC Spawn

**Set a timer** named *depop* for 140 seconds


## Combat

if a reanimated drudge enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

if(e.timer == "depop") then


**a reanimated drudge despawns.**
end
