# Frostpaw


## On NPC Spawn

**Set a timer** named *follow* for 150 seconds


## Timer(s)

if(**spawned NPC:**  [Wolfmaster Gunnar](/npc/115101)) then


eq.follow(eq.get_entity_list():GetMobByNpcTypeID( [Wolfmaster Gunnar](/npc/115101)):GetID());
end
