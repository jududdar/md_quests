# Brynju Thunderclap
## Combat

if  Brynju Thunderclap enters combat  then


**Set a timer** named *leash* for 30 seconds

else


**Stop timer** named *leash*
end

## Timer(s)


if ( e.timer == "leash" ) then



if ( e.self:GetZ() < 2200 ) then



e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());

end