# Bazzt Zzzt



[Bazzt Zzzt](/npc/71072) is a level 63 Bixie Shadow Knight that spawns in [Plane of Sky (Instanced)](/zone/1071).



## On NPC Spawn

**Set a timer** named *depop* for 4800 seconds


## Timer(s)

if(e.timer == "depop") then


**Bazzt Zzzt despawns.**
end



## On NPC Death

local sirranName = "sirran";

sirranName = sirranName .. eq.get_zone_guild_id();

eq.set_global(sirranName,"6",3,"M20");

**Spawn NPC:**  [Sirran the Lunatic](/npc/71058) at (**y:** -1078, **x:** 234)




