# Initiate Corrith



[Initiate Corrith](/npc/115205) is a level 32 Coldain Warrior that spawns in [The City of Thurgadin](/zone/115).





## On NPC Spawn

eq.set_timer("fight",math.random(30000) + 10000);


## Timer(s)

e.self:DoAnim(2);

e.self:DoAnim(7);

if(**spawned NPC:**  [Initiate Sircthain](/npc/115176)) then


eq.get_entity_list():GetMobByNpcTypeID( [Initiate Sircthain](/npc/115176)):CastToNPC():DoAnim(2);
end
