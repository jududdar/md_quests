# War Chieftan Birak

local INVIS_MAN_ID = 369487;

## On NPC Spawn

**Set a timer** named *check* for 1 seconds
## Timer(s)

eq.stop_timer(e.timer);

if ( **spawned NPC:**  [A Stonefist Clansman](/npc/222009) ) then 


**War Chieftan Birak despawns.**


return;
end

## On NPC Death

eq.get_entity_list():GetSpawnByID(INVIS_MAN_ID):GetNPC():Depop(true);

**Signaled to:**  [The](/npc/222034)