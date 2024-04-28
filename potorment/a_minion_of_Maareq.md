# a minion of Maareq
## On NPC Spawn



**Set a timer** named *check* for 1 seconds
## Timer(s)



local boss = eq.get_entity_list():GetMobByNpcTypeID( [Maareq the Prophet](/npc/207004)); 

if ( not boss or not boss.valid ) then


**a minion of Maareq despawns.**



if ( e.timer == "check" ) then


if ( e.self:CalculateDistance(boss:GetX(), boss:GetY(), boss:GetZ()) < 10 ) then



**Signaled to:**  [Maareq the Prophet](/npc/207004)



>*a minion of Maareq adheres to Maareq's flesh and is quickly absorbed!*



**a minion of Maareq despawns.**





elseif ( e.timer == "move" ) then


e.self:MoveTo(boss:GetX(), boss:GetY(), boss:GetZ(), -1, true);
end