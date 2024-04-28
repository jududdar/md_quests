# Nir-Tan


## Combat


if  Nir-Tan enters combat  then


**Set a timer** named *help* for 300 seconds


HelpMe(e);

else


**Stop timer** named *help*
end

## Timer(s)

if(e.timer == "help") then


HelpMe(e);
end

function HelpMe(e)

local aaryonar = eq.get_entity_list():GetMobByNpcTypeID(124010);



if (aaryonar.valid) then


aaryonar:CastToNPC():MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0, false);
end
