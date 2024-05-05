# Dread



[Dread](/npc/72000) is a level 55 Golem Warrior that spawns in [Plane of Fear](/zone/72).





## Signals

if(e.signal == 1) then


>**Dread says:** Such is the will of Cazic-Thule!
end



## On NPC Death

local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 2.0 and math.random(100) > 24) then


**Spawn NPC:**  [Iksar broodling](/npc/72105) at this location.
end
