# A Phoenix Scorchlet



[A Phoenix Scorchlet](/npc/215431) is a level 46 Phoenix Warrior that spawns in [Plane of Air](/zone/215).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Combat

if  A Phoenix Scorchlet enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## Timer(s)

if ( e.timer == "depop" and not e.self:Charmed() ) then


**A Phoenix Scorchlet despawns.**
end
