# Guard Kizzburr

[Guard Kizzburr](/npc/68025) is a level 25 Dwarf Warrior that spawns in [Butcherblock Mountains](/zone/68).

Their primary faction is [Storm Guard](/faction/312).



## Arrive at Waypoint Script

if (e.wp == 2) then

if(**spawned NPC:**  [a dwarven bandit](/npc/68011) == false) then

>**Guard Kizzburr says:** WARNING TO ALL TRAVELERS! Bandits have been sighted on the road ahead. Beware!

**Spawn NPC:**  [a dwarven bandit](/npc/68011) at (**y:** 1094, **x:** -510)



**Set a timer** named *warning* for 36 seconds









## Depart from Waypoint Script

if (e.wp == 2) then

**Stop timer** named *warning*









## Timer(s)

if(e.timer == "warning") then

>**Guard Kizzburr says:** WARNING TO ALL TRAVELERS! Bandits have been sighted on the road ahead. Beware!



