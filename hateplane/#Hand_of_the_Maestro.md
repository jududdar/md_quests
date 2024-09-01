# Hand of the Maestro

[Hand of the Maestro](/npc/76382) is a level 17 Reanimated Hand Warrior that spawns in [Plane of Hate](/zone/76).

Their primary faction is [Inhabitants of Hate](/faction/425).

function event_death_complete(event)



if(eq.is_the_ruins_of_kunark_enabled()) then

eq.spawn2(76388, 0, 0, event.self:GetX(), event.self:GetY(), event.self:GetZ(), event.self:GetHeading());



