# a muddy corpse



[a muddy corpse](/npc/160006) is a level 35 Zombie Warrior that spawns in [Katta Castellum](/zone/160).



## On NPC Spawn

**Set a timer** named *depop* for 120 seconds


## Timer(s)

if(e.timer == "depop") then


**a muddy corpse despawns.**
end



## Combat

if a muddy corpse enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
