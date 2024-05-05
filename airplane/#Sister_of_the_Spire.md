# Sister of the Spire



[Sister of the Spire](/npc/71076) is a level 65 Djinn Magician that spawns in [Plane of Sky](/zone/71).



## On NPC Death

local sirranName = "sirran";

sirranName = sirranName .. eq.get_zone_guild_id();

if(**spawned NPC:**  [Sirran the Lunatic](/npc/71058) == false) then


eq.set_global(sirranName,"7",3,"M20");


**Spawn NPC:**  [Sirran the Lunatic](/npc/71058) at (**y:** -1037, **x:** -960)
end





