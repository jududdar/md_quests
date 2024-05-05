# a Knight of Innoruuk



[a Knight of Innoruuk](/npc/76021) is a level 51 Dark Elf Shadow Knight that spawns in [Plane of Hate](/zone/76).

function event_signal(event)


if ( event.signal == 1 ) then




entityList = eq.get_entity_list();


local evangelist = entityList:GetNPCByNPCTypeID(76026);







if ( evangelist:CalculateDistance(event.self:GetX(), event.self:GetY(), event.self:GetZ()) < 60 ) then



event.self:Shout("All praise Innoruuk, our lord and creator!");

end
