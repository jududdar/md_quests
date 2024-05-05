# A Very Unpleasant Hand



[A Very Unpleasant Hand](/npc/76388) is a level 55 Reanimated Hand Warrior that spawns in [Plane of Hate (Instanced)](/zone/1076).

function event_spawn(event)

**Set a timer** named *depop* for 2700 seconds
function event_timer(event)


if ( event.self:IsEngaged() ) then


**Set a timer** named *depop* for 10 seconds





else


**A Very Unpleasant Hand despawns.**


**Stop timer** named *depop*
end
