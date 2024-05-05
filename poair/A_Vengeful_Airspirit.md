# A Vengeful Airspirit



[A Vengeful Airspirit](/npc/215413) is a level 46 Animated Armor Warrior that spawns in [Plane of Air](/zone/215).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Combat

if  A Vengeful Airspirit enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## Timer(s)

if ( e.timer == "depop" and not e.self:Charmed() ) then


**A Vengeful Airspirit despawns.**
end
