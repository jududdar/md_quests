# Frostpaw



[Frostpaw](/npc/115183) is a level 38 Wolf Warrior that spawns in [The City of Thurgadin](/zone/115).



## On NPC Spawn

**Set a timer** named *follow* for 150 seconds


## Timer(s)

if(**spawned NPC:**  [Wolfmaster Gunnar](/npc/115101)) then


eq.follow(eq.get_entity_list():GetMobByNpcTypeID( [Wolfmaster Gunnar](/npc/115101)):GetID());
end
