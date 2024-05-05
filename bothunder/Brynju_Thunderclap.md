# Brynju Thunderclap



[Brynju Thunderclap](/npc/209016) is a level 67 Giant Warrior that spawns in [Bastion of Thunder](/zone/209).



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
