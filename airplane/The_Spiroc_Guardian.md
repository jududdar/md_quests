# The Spiroc Guardian
## On NPC Death

**Signaled to:**  [a spiroc walker](/npc/71014)

**Signaled to:**  [a spiroc banisher](/npc/71007)

**Signaled to:**  [a spiroc revolter](/npc/71010)
## On NPC Spawn

**Set a timer** named *lord* for 1 seconds
## Signals

if ( e.signal == 1 ) then


**Set a timer** named *lord* for 1 seconds
end

## Timer(s)

if ( e.self:IsEngaged() or e.self:Charmed() or e.self:GetX() ~= e.self:GetSpawnPointX() or e.self:GetY() ~= e.self:GetSpawnPointY() ) then


return;



if ( not **spawned NPC:**  [The Spiroc Lord](/npc/71012) ) then 


**Spawn NPC from spawn group:** [The Spiroc Lord](/npc/364318) after 1 second(s)

eq.stop_timer(e.timer);