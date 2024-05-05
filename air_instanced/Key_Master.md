# Key Master



[Key Master](/npc/71056) is a level 55 Dwarf Shopkeeper that spawns in [Plane of Sky (Instanced)](/zone/1071).



## Signals

local qglobals = eq.get_qglobals();

local keeperName = "keeper";

keeperName = keeperName .. eq.get_zone_guild_id();

if(e.signal == 1) then 


if(**spawned NPC:**  [an azarack](/npc/71111) == false and **spawned NPC:** 71031 == false) then



**Spawn NPC:**  [Protector of Sky](/npc/71559) at (**y:** -254.4, **x:** -602.2)


if(e.signal == 2) then


if(qglobals[keeperName] == nil) then







eq.set_global(keeperName,"1",3,"H1");



**Spawn NPC:**  [Keeper of Souls](/npc/71575) at (**y:** 720, **x:** -1484)









end



## Dialog

**You say:** `hail`



>**Key Master says:** Hello there, brave traveller. I sell keys that take you to other islands in this here Plane of Sky. My prices are the best around. Heh, heh.
end



## Timer(s)

if(e.timer == "soul") then


**Stop timer** named *soul*
end

