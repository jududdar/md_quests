# a smuggler
## Signals

if(e.signal == 1) then


>**a smuggler says:** The boss might need some help!


local stanos = eq.get_entity_list():GetMobByNpcTypeID(5088); 


if ( stanos.valid ) then



e.self:MoveTo(stanos:GetX(), stanos:GetY(), stanos:GetZ(), -1, false);

end