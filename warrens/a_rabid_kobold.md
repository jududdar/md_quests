# a rabid kobold



[a rabid kobold](/npc/101029) is a level 5 Kobold Warrior that spawns in [The Warrens](/zone/101).



## On NPC Death

local spawna = **Spawn NPC:**  [a kobold master blacksmith](/npc/101006) at (**y:** 713, **x:** -866)

local spawnb = **Spawn NPC:**  [a kobold master blacksmith](/npc/101006) at (**y:** 577, **x:** -473)

local spawnc = **Spawn NPC:**  [a kobold master blacksmith](/npc/101006) at (**y:** 506, **x:** -1019)



if(math.random(100) < 5) then


RandomSpawn = eq.ChooseRandom(spawna,spawnb,spawnc);
end