# a dandy pansy



[a dandy pansy](/npc/126002) is a level 48 Man-Eating Plant Warrior that spawns in [Plane of Mischief](/zone/126).



## On NPC Spawn

**Set a timer** named *depop* for 300 seconds


## Combat

if a dandy pansy enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

**a dandy pansy despawns.**
end