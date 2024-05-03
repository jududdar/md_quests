# Duster V




## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds


## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*Duster V clicks as a plate slides to the side revealing a hose that extends and sucks up an item from the ground*




## Arrive at Waypoint Script

if(e.wp == 30) then


>**Duster V says:** Click.. Dust. Dust. Dust.

elseif(e.wp == 42) then


>**Duster V says:** Click.. Dust. Dust. Dust.


e.self:SetRunning(true);
end
