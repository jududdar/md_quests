# Mazrien




## Combat


if  Mazrien enters combat  then


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

local koi = eq.get_entity_list():GetMobByNpcTypeID(124103);



if (koi.valid) then


koi:CastToNPC():MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0, false);
end
