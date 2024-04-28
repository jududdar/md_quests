# Beef
## Signals

if(e.signal == 1) then


>**Beef says:** The boss might need some help!


local stanos = eq.get_entity_list():GetMobByNpcTypeID(5088); 


if ( stanos.valid ) then



e.self:MoveTo(stanos:GetX(), stanos:GetY(), stanos:GetZ(), -1, false);


elseif(e.signal == 2) then


>**Beef says:** Gets moving before me smash yu to pulp!!

elseif(e.signal == 3) then


>**Beef says:** BWAHAHA HA!! Yoo werk fer Mister Axe now. Hehehe!!
end

## Dialog

**You say:** `hail`



>**Beef says:** Yu be getting going. Dis here is da boss' table!!
end
