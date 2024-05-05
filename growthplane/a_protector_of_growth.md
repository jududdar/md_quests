# a protector of growth



[a protector of growth](/npc/127003) is a level 55 Yakkar Ranger that spawns in [Plane of Growth](/zone/127).



## On NPC Spawn

if(**spawned NPC:**  [\#a protector of growth](/npc/127005) == false) then


**Set a timer** named *chance* for 1 seconds
end



## Timer(s)

if(e.timer == "chance") then


**Stop timer** named *chance*


if(math.random(2) == 1) then



**Spawn NPC:**  [\#a protector of growth](/npc/127005) at (**y:** -196, **x:** -1006)

end
