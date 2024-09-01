# Untel`Dak

[Untel`Dak](/npc/204035) is a level 68 Crocodile Warrior that spawns in [Plane of Nightmares](/zone/204).

Their primary faction is [KOS Plane of Nightmare](/faction/5029).

## Combat
if  Untel-Dak enters combat  then
**Set a timer** named *boundscheck* for 3 seconds
else
**Stop timer** named *boundscheck*





## Timer(s)

if ( e.timer == "boundscheck" ) then
if ( e.self:GetY() > -1550 ) then
**Untel-Dak** clears hate list.
e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());


