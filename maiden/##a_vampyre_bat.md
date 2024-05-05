# a vampyre bat



[a vampyre bat](/npc/173007) is a level 46 Bat Warrior that spawns in [The Maiden's Eye](/zone/173).



## On NPC Spawn

**Set a timer** named *depop* for 140 seconds


## Combat

if a vampyre bat enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

if(e.timer == "depop") then


**a vampyre bat despawns.**
end
