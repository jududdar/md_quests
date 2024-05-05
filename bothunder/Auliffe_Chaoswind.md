# Auliffe Chaoswind



[Auliffe Chaoswind](/npc/209059) is a level 67 Giant Cleric that spawns in [Bastion of Thunder](/zone/209).



## Combat

if  Auliffe Chaoswind enters combat  then


**Set a timer** named *leash* for 30 seconds

else


**Stop timer** named *leash*
end



## Timer(s)


if ( e.timer == "leash" ) then



if ( e.self:GetZ() < 1400 ) then



e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());

end
