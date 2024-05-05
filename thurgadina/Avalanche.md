# Avalanche



[Avalanche](/npc/115184) is a level 39 Wolf Warrior that spawns in [The City of Thurgadin](/zone/115).



## On NPC Spawn

**Set a timer** named *follow* for 150 seconds


## Timer(s)

if(**spawned NPC:**  [Wolfmaster Berglind](/npc/115102)) then


eq.follow(eq.get_entity_list():GetMobByNpcTypeID( [Wolfmaster Berglind](/npc/115102)):GetID());
end
