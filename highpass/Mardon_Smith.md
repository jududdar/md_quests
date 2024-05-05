# Mardon Smith



[Mardon Smith](/npc/5060) is a level 45 Human Shopkeeper that spawns in [Highpass Hold](/zone/5).



## Signals

if(e.signal == 1) then


>**Mardon Smith says:** The boss might need some help!


local stanos = eq.get_entity_list():GetMobByNpcTypeID(5088); 


if ( stanos.valid ) then



e.self:MoveTo(stanos:GetX(), stanos:GetY(), stanos:GetZ(), -1, false);

end