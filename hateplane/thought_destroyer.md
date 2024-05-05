# thought destroyer



[thought destroyer](/npc/76387) is a level 55 Zombie Bard that spawns in [Plane of Hate](/zone/76).

function event_spawn(event)

**Set a timer** named *depop* for 1200 seconds
function event_timer(event)


if ( event.self:IsEngaged() ) then


**Set a timer** named *depop* for 10 seconds





else


**thought destroyer despawns.**


**Stop timer** named *depop*
end
