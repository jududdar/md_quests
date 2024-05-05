# Kobot Dellin



[Kobot Dellin](/npc/12165) is a level 4 Human Paladin that spawns in [Western Plains of Karana](/zone/12).



## On NPC Spawn

e.self:SetRunning(true);


## Dialog

**You say:** `hail`



>**Kobot Dellin says:** No time to talk!! I must be on my way. I am in a race with the paladins from the Temple of Life.
end

function event_death(e)

local sp = e.self:GetSpawnPointID();

local spawn = eq.get_entity_list():GetSpawnByID(sp);

spawn:SetRespawnTimer(840);