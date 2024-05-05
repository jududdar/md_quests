# a scorn banshee



[a scorn banshee](/npc/76302) is a level 49 Zombie Bard that spawns in [Plane of Hate](/zone/76).

function event_death_complete(event)



if ( math.random() < 0.05 ) then


eq.spawn2(76387, 0, 0, event.self:GetX(), event.self:GetY(), event.self:GetZ(), event.self:GetHeading());
end
