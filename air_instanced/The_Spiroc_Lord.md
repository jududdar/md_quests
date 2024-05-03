# The Spiroc Lord


## On NPC Death

local qglobals = eq.get_qglobals();


local sirranName = "sirran";

sirranName = sirranName .. eq.get_zone_guild_id();



if(qglobals[sirranName] ~= "5" and (**spawned NPC:**  [a spiroc vanquisher](/npc/71009) == false or **spawned NPC:** 71020 == false or **spawned NPC:** 71022 == false)) then


eq.set_global(sirranName,"5",3,"M20");


**Spawn NPC:**  [Sirran the Lunatic](/npc/71058) at (**y:** -570, **x:** 955)



**Signaled to:**  [The Spiroc Guardian](/npc/71013)