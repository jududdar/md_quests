# a mind burrower



[a mind burrower](/npc/173003) is a level 52 Worm Warrior that spawns in [The Maiden's Eye](/zone/173).



## On NPC Spawn

**Set a timer** named *depop* for 140 seconds


## Combat

if a mind burrower enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

if(e.timer == "depop") then


**a mind burrower despawns.**
end
