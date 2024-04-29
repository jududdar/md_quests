# Guard Haldin
## Arrive at Waypoint Script

if (e.wp == 2) then


if(**spawned NPC:**  [a dwarven bandit](/npc/68011) == false) then



>**Guard Haldin says:** WARNING TO ALL TRAVELERS! Bandits have been sighted on the road ahead. Beware!



**Spawn NPC:**  [a dwarven bandit](/npc/68011) at (**y:** 1094, **x:** -510)



**Set a timer** named *warning* for 36 seconds
end

## Depart from Waypoint Script

if (e.wp == 2) then


**Stop timer** named *warning*
end

## Timer(s)

if(e.timer == "warning") then


>**Guard Haldin says:** WARNING TO ALL TRAVELERS! Bandits have been sighted on the road ahead. Beware!
end

## Turn-Ins



if( **You turn in:** [A Worn Rune](/item/18905)) then


>**Guard Haldin says:** Eh, strapling? Ye got this from me ol' partner? Huh. Aye, I know what it means but ye're not hearin'. Here, take this. It was his but he's not needin' it now.


 **You receive:** eq.ChooseRandom( [Bronze Battle Axe](/item/5028), [Dwarven Axe](/item/5300)) (+30000 exp)
end
