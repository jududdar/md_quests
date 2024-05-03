# Vhaksiz the Shade
local x, y, z;



## On NPC Spawn

x = e.self:GetX();

y = e.self:GetY();

z = e.self:GetZ();


## Combat

if  Vhaksiz the Shade enters combat  then


**Set a timer** named *leashcheck* for 3 seconds

else


**Stop timer** named *leashcheck*
end



## Timer(s)

if ( e.timer == "leashcheck" ) then


if ( e.self:CalculateDistance(x, y, z) > 155 ) then



**Vhaksiz the Shade** clears hate list.



e.self:GMMove(x, y, z, e.self:GetSpawnPointH());



**Vhaksiz the Shade casts:** [Annul Self](/spell/2830) on themselves.

end
