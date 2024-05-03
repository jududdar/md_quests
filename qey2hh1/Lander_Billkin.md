# Lander Billkin


## On NPC Spawn

e.self:SetRunning(true);


## Dialog

**You say:** `hail`



>**Lander Billkin says:** No time to talk!! I must be on my way. I am in a race with the paladins from the Temple of Life.
end

function event_death(e)

local sp = e.self:GetSpawnPointID();

local spawn = eq.get_entity_list():GetSpawnByID(sp);

spawn:SetRespawnTimer(840);