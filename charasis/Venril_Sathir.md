# Venril Sathir
local counting;



## On NPC Spawn

**Set a timer** named *combat* for 20 seconds

counting = 0;


## Timer(s)

if (e.timer == "combat") then


counting = counting + 1;

if(counting == 2) then


**Venril Sathir attacks NPC:**  [Rile Sathir](/npc/105004)

elseif(counting == 3) then


**Spawn NPC:**  [\#Venril Sathir](/npc/105182) at this location.


**Spawn NPC:**  [\#an Arisen Disciple](/npc/105022) at (**y:** -658, **x:** -13)


**Spawn NPC:**  [\#an Arisen Priest](/npc/105023) at (**y:** -658, **x:** 13)


**Spawn NPC:**  [\#an Arisen Necromancer](/npc/105024) at (**y:** -690, **x:** 13)


**Spawn NPC:**  [\#an Arisen Acolyte](/npc/105025) at (**y:** -690, **x:** -13)


**Despawn NPC:**  [Rile Sathir](/npc/105004)


**Despawn NPC:**  [an Arisen Disciple](/npc/105186)


**Despawn NPC:**  [an Arisen Priest](/npc/105183)


**Despawn NPC:**  [an Arisen Necromancer](/npc/105184)


**Despawn NPC:**  [an Arisen Acolyte](/npc/105185)


**Venril Sathir despawns.**
end
