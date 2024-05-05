# an Agent of Innoruuk



[an Agent of Innoruuk](/npc/76383) is a level 53 Dark Elf Rogue that spawns in [Plane of Hate](/zone/76).

function event_signal(event)


if ( event.signal == 1 ) then




entityList = eq.get_entity_list();


local evangelist = entityList:GetNPCByNPCTypeID(76026);







if ( evangelist:CalculateDistance(event.self:GetX(), event.self:GetY(), event.self:GetZ()) < 60 ) then



event.self:Shout("All praise Innoruuk, our lord and creator!");

end
