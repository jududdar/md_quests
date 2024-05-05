# a coterie general



[a coterie general](/npc/172185) is a level 46 Vampire Warrior that spawns in [The Tenebrous Mountains](/zone/172).



## On NPC Spawn

**Set a timer** named *depop* for 300 seconds


## Timer(s)

if(e.timer == "depop") then


**a coterie general despawns.**
end



## Combat

if a coterie general enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end