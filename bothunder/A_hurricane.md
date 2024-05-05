# A hurricane



[A hurricane](/npc/209125) is a level 66 Elemental Rogue that spawns in [Bastion of Thunder](/zone/209).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**A hurricane despawns.**
end



## Combat

if  A hurricane enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
