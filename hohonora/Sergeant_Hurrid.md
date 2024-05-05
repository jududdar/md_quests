# Sergeant Hurrid



[Sergeant Hurrid](/npc/211031) is a level 65 Valorian Warrior that spawns in [Halls of Honor](/zone/211).



## On NPC Spawn

**Set a timer** named *formation* for 55 seconds


## Timer(s)

if ( e.timer == "formation" ) then


if ( e.self:GetX() == e.self:GetSpawnPointX() and e.self:GetY() == e.self:GetSpawnPointY() ) then



>**Sergeant Hurrid says:** Stay in formation!



**Signaled to:**  [An Imperon Servicemen](/npc/211029)

end
