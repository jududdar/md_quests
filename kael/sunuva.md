# sunuva


## On NPC Spawn

**Set a timer** named *proxsay* for 2 seconds
 

## Timer(s)

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

eq.set_proximity(xloc - 14, xloc + 20, yloc - 10, yloc + 10);

eq.enable_proximity_say();

**Stop timer** named *proxsay*
 
function event_proximity_say(e)

local xloc = e.other:GetX();

local yloc = e.other:GetY();

local nxloc = e.self:GetX();

local nyloc = e.self:GetY();

local xdiff = xloc - nxloc;

local ydiff = yloc - nyloc;

**You say:** `hail`



>**sunuva says:** Your x is ".. xdiff .." and your y is " .. ydiff .." from me!

**You say:** `the dain shall be slain for the peace we must obtain`



if(eq.get_entity_list():IsMobSpawnBySpawnID(337949) == false 


and eq.get_entity_list():IsMobSpawnBySpawnID(337959) == false 


and eq.get_entity_list():IsMobSpawnBySpawnID(337948) == false 


and eq.get_entity_list():IsMobSpawnBySpawnID(337960) == false 


and eq.get_entity_list():IsMobSpawnBySpawnID(337847) == false


and eq.get_entity_list():IsMobSpawnBySpawnID(337960) == false


and **spawned NPC:**  [\#Doldigun Steinwielder](/npc/113260) == false


and **spawned NPC:**  [Grondon Zekkin](/npc/113261) == false


and **spawned NPC:**  [Kromzog Zekkin](/npc/113262) == false


and **spawned NPC:**  [Vinric Thunderclap](/npc/113263) == false


and **spawned NPC:**  [Zlirron Windchill](/npc/113264) == false


and **spawned NPC:**  [Khalerogg Dorfenbane](/npc/113265) == false


and **spawned NPC:**  [Valorankt Zekkin](/npc/113266) == false) then



**Spawn NPC:**  [Doldigun Steinwielder](/npc/113249) at this location.

end
