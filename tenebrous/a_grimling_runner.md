# a grimling runner



[a grimling runner](/npc/172060) is a level 34 Grimling Rogue that spawns in [The Tenebrous Mountains](/zone/172).



## On NPC Spawn

**Set a timer** named *depop* for 1620 seconds


## Timer(s)

if(e.timer == "depop") then


**a grimling runner despawns.**
end



## Combat

if a grimling runner enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Arrive at Waypoint Script

if(e.wp == 10) then


>**a grimling runner says:** I'm here for the next ore shipment comrades!
end
