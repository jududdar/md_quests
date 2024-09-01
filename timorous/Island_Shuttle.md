# Island Shuttle

[Island Shuttle](/npc/96075) is a level 50 Launch Warrior that spawns in [Timorous Deep](/zone/96).

## On NPC Spawn

if (eq.get_zone_guild_id() ~= -1) then

eq.debug("We are in an instance (" .. eq.get_zone_guild_id() .. "), ignoring event_spawn for " .. e.self:GetName());

**Island Shuttle despawns.**









## Signals

if(e.signal == 1) then

eq.start(3);

elseif(e.signal == 2) then

eq.stop();



