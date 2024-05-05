# A storm cloud



[A storm cloud](/npc/209130) is a level 61 Elemental Warrior that spawns in [Bastion of Thunder](/zone/209).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**A storm cloud despawns.**
end



## Combat

if  A storm cloud enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
