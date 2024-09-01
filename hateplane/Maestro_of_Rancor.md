# Maestro of Rancor

[Maestro of Rancor](/npc/76006) is a level 53 Vampire Wizard that spawns in [Plane of Hate](/zone/76).

Their primary faction is [Inhabitants of Hate](/faction/425).function event_death_complete(event)

if(is_current_expansion_the_ruins_of_kunark()) then
eq.spawn2(76382, 0, 0, event.self:GetX(), event.self:GetY(), event.self:GetZ(), event.self:GetHeading());

