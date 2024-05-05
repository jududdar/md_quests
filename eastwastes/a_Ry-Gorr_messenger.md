# a Ry\`Gorr messenger



[a Ry\`Gorr messenger](/npc/116211) is a level 27 Orc Warrior that spawns in [Eastern Wastes](/zone/116).



## On NPC Spawn

e.self:SetRunning(true);

local sp = e.self:GetSpawnPointID();

local spawn = eq.get_entity_list():GetSpawnByID(sp);

spawn:SetRespawnTimer(5);
function event_death(e)

local sp = e.self:GetSpawnPointID();

local spawn = eq.get_entity_list():GetSpawnByID(sp);

spawn:SetRespawnTimer(14400);