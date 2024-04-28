# You stumble


## On NPC Spawn

eq.set_proximity(e.self:GetX() - 50, e.self:GetX() + 50, e.self:GetY() - 50, e.self:GetY() + 50);
function event_enter(e)

if(**spawned NPC:**  [Tanik Greskil](/npc/116010)) then


>*You stumble in the snow.*

else


>*You stumble and uncover the body of an injured coldain.*


**Spawn NPC:**  [Tanik Greskil](/npc/116010) at this location.


**You stumble despawns.**
end
