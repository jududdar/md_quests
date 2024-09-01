# King Kazon Stormhammer

[King Kazon Stormhammer](/npc/60007) is a level 50 Dwarf Warrior that spawns in [South Kaladim](/zone/60).

Their primary faction is [Kazon Stormhammer](/faction/274).

## Combat

**Spawn NPC:**  [a Bloodforge Captain](/npc/60004) at (**y:** -200, **x:** -360)

**Spawn NPC:**  [Bloodforge Brigade](/npc/60005) at (**y:** -200, **x:** -360)

**Set a timer** named *Bloodforge* for 1 seconds







## Timer(s)

if(e.timer == "Bloodforge") then

**Stop timer** named *Bloodforge*

eq.get_entity_list():GetMobByNpcTypeID(60004):CastToNPC():SetRunning(true);

eq.get_entity_list():GetMobByNpcTypeID(60005):CastToNPC():SetRunning(true);

eq.get_entity_list():GetMobByNpcTypeID(60004):CastToNPC():MoveTo(e.self:GetX(),e.self:GetY(),e.self:GetZ(),0,true);

eq.get_entity_list():GetMobByNpcTypeID(60005):CastToNPC():MoveTo(e.self:GetX(),e.self:GetY(),e.self:GetZ(),0,true);

eq.get_entity_list():GetMobByNpcTypeID(60004):Say("I am coming, my liege!");

eq.get_entity_list():GetMobByNpcTypeID(60005):Say("I am coming, my liege!");



