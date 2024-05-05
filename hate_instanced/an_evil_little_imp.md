# an evil little imp



[an evil little imp](/npc/76386) is a level 48 Imp Warrior that spawns in [Plane of Hate (Instanced)](/zone/1076).

function event_spawn(event)

**Set a timer** named *depop* for 1200 seconds
function event_timer(event)


if ( event.self:IsEngaged() ) then


**Set a timer** named *depop* for 10 seconds





else


**an evil little imp despawns.**


**Stop timer** named *depop*
end
