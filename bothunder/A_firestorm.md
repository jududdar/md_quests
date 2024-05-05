# A firestorm



[A firestorm](/npc/209124) is a level 62 Elemental Wizard that spawns in [Bastion of Thunder](/zone/209).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**A firestorm despawns.**
end



## Combat

if  A firestorm enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
