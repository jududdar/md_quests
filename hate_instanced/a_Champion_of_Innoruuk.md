# a Champion of Innoruuk



[a Champion of Innoruuk](/npc/76087) is a level 54 Dark Elf Warrior that spawns in [Plane of Hate (Instanced)](/zone/1076).

function event_signal(event)


if ( event.signal == 1 ) then




entityList = eq.get_entity_list();


local evangelist = entityList:GetNPCByNPCTypeID(76026);







if ( evangelist:CalculateDistance(event.self:GetX(), event.self:GetY(), event.self:GetZ()) < 60 ) then



event.self:Shout("All praise Innoruuk, our lord and creator!");

end
