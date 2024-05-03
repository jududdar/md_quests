# Kyle Rinlin


## On NPC Spawn

e.self:SetRunning(true);


## Dialog

**You say:** `hail`



>**Kyle Rinlin says:** No time to talk!! I must be off. The grains of sand are falling and I must prove that we paladins from the Temple of Thunder are the quickest.
end

function event_death(e)

local sp = e.self:GetSpawnPointID();

local spawn = eq.get_entity_list():GetSpawnByID(sp);

spawn:SetRespawnTimer(840);