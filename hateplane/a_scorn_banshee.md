# a scorn banshee

[a scorn banshee](/npc/76302) is a level 49 Zombie Bard that spawns in [Plane of Hate](/zone/76).

Their primary faction is [Inhabitants of Hate](/faction/425).function event_death_complete(event)

if(eq.is_the_ruins_of_kunark_enabled()) then
if ( math.random() < 0.15 ) then
eq.spawn2(76387, 0, 0, event.self:GetX(), event.self:GetY(), event.self:GetZ(), event.self:GetHeading());


