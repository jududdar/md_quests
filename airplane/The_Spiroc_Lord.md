# The Spiroc Lord

[The Spiroc Lord](/npc/71012) is a level 63 Aviak Ranger that spawns in [Plane of Sky](/zone/71).

Their primary faction is [KOS](/faction/5017).



## On NPC Death

local qglobals = eq.get_qglobals();

local sirranName = "sirran";

sirranName = sirranName .. eq.get_zone_guild_id();



if(qglobals[sirranName] ~= "5" and (**spawned NPC:**  [a spiroc vanquisher](/npc/71009) == false or **spawned NPC:**  [a spiroc vanquisher](/npc/71020) == false or **spawned NPC:**  [a spiroc vanquisher](/npc/71022) == false)) then

eq.set_global(sirranName,"5",3,"M20");

**Spawn NPC:**  [Sirran the Lunatic](/npc/71058) at this location.





**Signaled to:**  [The Spiroc Guardian](/npc/71013)

