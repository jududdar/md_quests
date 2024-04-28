# Rizlona
## On NPC Death

**Spawn NPC:**  [\#Rizlona](/npc/212407) at this location.

## Combat

if  Rizlona enters combat  then


**Set a timer** named *bounds* for 6 seconds

else


**Stop timer** named *bounds*
end

## Timer(s)


if ( e.timer == "bounds" ) then




if ( e.self:GetY() < 2047 or e.self:GetY() > 2538 ) then



e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());



**Rizlona** clears hate list.



**Rizlona casts:** [Annul Self](/spell/2830) on themselves.

end
