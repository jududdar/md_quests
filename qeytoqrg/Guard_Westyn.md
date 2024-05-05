# Guard Westyn



[Guard Westyn](/npc/4033) is a level 30 Human Warrior that spawns in [Qeynos Hills](/zone/4).



## Dialog

**You say:** `blackburrow`



>**Guard Westyn says:** Blast those dogs!  The Sabertooths is what they call themselves around here.  They have a nest, or whatever you call it, up there east of Surefall Glade.  We can always use help here, keeping those dirty gnolls away from our fine city.  Talk to Captain Tillin in South Qeynos and tell him you want to join the fight.
end



## Arrive at Waypoint Script

if(e.wp == 1 or e.wp == 6) then


e.self:SetRunning(true);

elseif(e.wp == 4 or e.wp == 7) then


e.self:SetRunning(false);
end
