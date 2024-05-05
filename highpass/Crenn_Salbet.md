# Crenn Salbet



[Crenn Salbet](/npc/5053) is a level 38 Human Rogue that spawns in [Highpass Hold](/zone/5).



## Signals

if(e.signal == 1) then


>**Crenn Salbet says:** The boss might need some help!


local stanos = eq.get_entity_list():GetMobByNpcTypeID(5088); 


if ( stanos.valid ) then



e.self:MoveTo(stanos:GetX(), stanos:GetY(), stanos:GetZ(), -1, false);

end