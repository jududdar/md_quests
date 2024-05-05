# Scar



[Scar](/npc/5134) is a level 18 Dark Elf Rogue that spawns in [Highpass Hold](/zone/5).



## Signals

if(e.signal == 1) then


>**Scar says:** The boss might need some help!


local stanos = eq.get_entity_list():GetMobByNpcTypeID(5088); 


if ( stanos.valid ) then



e.self:MoveTo(stanos:GetX(), stanos:GetY(), stanos:GetZ(), -1, false);

end