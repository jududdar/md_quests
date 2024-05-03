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



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18905" data-url="18905" class="tooltip-link link">A Worn Rune</a>) then


>**Guard Haldin says:** Eh, strapling? Ye got this from me ol' partner? Huh. Aye, I know what it means but ye're not hearin'. Here, take this. It was his but he's not needin' it now.


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5028" data-url="5028" class="tooltip-link link">Bronze Battle Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5300" data-url="5300" class="tooltip-link link">Dwarven Axe</a>) (+30000 exp)

 
end
