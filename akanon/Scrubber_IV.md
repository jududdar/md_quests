# Scrubber IV



[Scrubber IV](/npc/55221) is a level 8 Rat Warrior that spawns in [Ak'Anon](/zone/55).





## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds


## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*Scrubber IV clicks as a plate slides to the side revealing a hose that extends and sucks up an item from the ground*




## Arrive at Waypoint Script

if(e.wp == 30) then


>**Scrubber IV says:** Click.. Dust. Dust. Dust.

elseif(e.wp == 42) then


>**Scrubber IV says:** Click.. Dust. Dust. Dust.


e.self:SetRunning(true);
end
