# Avatar of Earth
local PLANAR_PROJECTION_TYPE = 222041; 



## On NPC Death

eq.spawn2(PLANAR_PROJECTION_TYPE, 0, 0, e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0);

eq.signal(PLANAR_PROJECTION_TYPE, e.killer:GetID()); 


## On NPC Spawn

**Set a timer** named *depop* for 2100 seconds


## Combat

if  Avatar of Earth enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## Timer(s)

if ( e.timer == "depop" ) then


eq.debug("Avatar of Earth depop");


**Avatar of Earth despawns.**
end
