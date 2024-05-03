# Guard Kizzburr


## Arrive at Waypoint Script

if (e.wp == 2) then


if(**spawned NPC:**  [a dwarven bandit](/npc/68011) == false) then



>**Guard Kizzburr says:** WARNING TO ALL TRAVELERS! Bandits have been sighted on the road ahead. Beware!



**Spawn NPC:**  [a dwarven bandit](/npc/68011) at (**y:** 1094, **x:** -510)



**Set a timer** named *warning* for 36 seconds
end



## Depart from Waypoint Script

if (e.wp == 2) then


**Stop timer** named *warning*
end



## Timer(s)

if(e.timer == "warning") then


>**Guard Kizzburr says:** WARNING TO ALL TRAVELERS! Bandits have been sighted on the road ahead. Beware!
end
