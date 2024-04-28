# Ambassador Rylan
## On NPC Spawn

local sp = e.self:GetSpawnPointID();

local spawn = eq.get_entity_list():GetSpawnByID(sp);

spawn:SetRespawnTimer(234);
function event_death(e)

local sp = e.self:GetSpawnPointID();

local spawn = eq.get_entity_list():GetSpawnByID(sp);

spawn:SetRespawnTimer(324);