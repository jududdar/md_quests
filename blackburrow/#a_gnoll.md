# a gnoll



[a gnoll](/npc/17003) is a level 5 Gnoll Warrior that spawns in [Blackburrow](/zone/17).



## On NPC Spawn

local sp = e.self:GetSpawnPointID();

local spawn = eq.get_entity_list():GetSpawnByID(sp);

spawn:SetRespawnTimer(230);

**Set a timer** named *depop* for 120 seconds


## Combat

if a gnoll enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

**Stop timer** named *depop*

**a gnoll despawns.**
function event_death(e)

local sp = e.self:GetSpawnPointID();

local spawn = eq.get_entity_list():GetSpawnByID(sp);

spawn:SetRespawnTimer(360);