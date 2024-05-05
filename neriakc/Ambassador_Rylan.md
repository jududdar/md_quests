# Ambassador Rylan



[Ambassador Rylan](/npc/42003) is a level 24 Dark Elf Warrior that spawns in [Neriak - 3rd Gate](/zone/42).



## On NPC Spawn

local sp = e.self:GetSpawnPointID();

local spawn = eq.get_entity_list():GetSpawnByID(sp);

spawn:SetRespawnTimer(234);
function event_death(e)

local sp = e.self:GetSpawnPointID();

local spawn = eq.get_entity_list():GetSpawnByID(sp);

spawn:SetRespawnTimer(324);