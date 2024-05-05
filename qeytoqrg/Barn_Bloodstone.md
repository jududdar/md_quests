# Barn Bloodstone



[Barn Bloodstone](/npc/4203) is a level 20 Human Rogue that spawns in [Qeynos Hills](/zone/4).



## Arrive at Waypoint Script

if(e.wp == 1 or e.wp == 6) then


e.self:SetRunning(true);

elseif(e.wp == 4 or e.wp == 7) then


e.self:SetRunning(false);
end



## Dialog

**You say:** `hail`



>**Barn Bloodstone says:** You seem a little out of place here. You should go back to the nice little village you came from. This place will eat you alive. The [Golden Rooster] is no place for you.

**You say:** `blackburrow stout`



>**Barn Bloodstone says:** Blackburrow Stout is the finest drink available. It is the nectar of the gods. Well.. nectar of the gnolls at least. I can't wait until they hold another drink special in the Rooster. When I hear that. I am there!

**You say:** `golden rooster`



>**Barn Bloodstone says:** The Golden Rooster only happens to be the finest gambling house in Highpass. It is also the only place in these parts that serves [Blackburrow Stout].
end