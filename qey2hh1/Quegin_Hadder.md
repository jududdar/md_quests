# Quegin Hadder



[Quegin Hadder](/npc/12164) is a level 4 Human Paladin that spawns in [Western Plains of Karana](/zone/12).



## On NPC Spawn

e.self:SetRunning(true);


## Dialog

**You say:** `hail`



>**Quegin Hadder says:** No time to talk!! I must be off. The grains of sand are falling and I must prove that we paladins from the Temple of Thunder are the quickest.
end

function event_death(e)

local sp = e.self:GetSpawnPointID();

local spawn = eq.get_entity_list():GetSpawnByID(sp);

spawn:SetRespawnTimer(840);