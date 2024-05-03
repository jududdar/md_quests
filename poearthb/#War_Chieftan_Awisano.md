# War Chieftan Awisano

local INVIS_MAN_ID = 369489;



## On NPC Spawn

**Set a timer** named *check* for 1 seconds


## Timer(s)

eq.stop_timer(e.timer);

if ( **spawned NPC:**  [A Myrmidon of Stone](/npc/222008) ) then 


**War Chieftan Awisano despawns.**


return;
end



## On NPC Death

eq.get_entity_list():GetSpawnByID(INVIS_MAN_ID):GetNPC():Depop(true);

**Signaled to:**  [The](/npc/222034)