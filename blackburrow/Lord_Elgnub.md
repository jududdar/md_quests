# Lord Elgnub

[Lord Elgnub](/npc/17029) is a level 21 Gnoll Shadow Knight that spawns in [Blackburrow](/zone/17).

Their primary faction is [Split Paw Clan](/faction/321).

## On NPC Spawn
local sp = e.self:GetSpawnPointID();
local spawn = eq.get_entity_list():GetSpawnByID(sp);
spawn:SetRespawnTimer(230);
**Set a timer** named *depop* for 120 seconds




## Combat
if Lord Elgnub enters combat  then
if(not eq.is_paused_timer("depop")) then
eq.pause_timer("depop");

else
eq.resume_timer("depop");





## Timer(s)
**Stop timer** named *depop*
**Lord Elgnub despawns.**


function event_death(e)
local sp = e.self:GetSpawnPointID();
local spawn = eq.get_entity_list():GetSpawnByID(sp);
spawn:SetRespawnTimer(360);
