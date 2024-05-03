# AirTrapSpawner


## Combat


if  AirTrapSpawner enters combat  then


eq.get_entity_list():MessageClose(e.self, true, 75, 0, "Storm clouds begin to gather over your head.");


**Set a timer** named *cast* for 5 seconds
end



## Timer(s)


if ( e.timer == "cast" ) then




local chance = 50;


if ( e.self:GetZ() > 0 ) then



chance = 75;







if ( math.random(100) > chance ) then



eq.get_entity_list():MessageClose(e.self, true, 75, 0, "The storm clouds pass harmlessly.");


else



**Spawn NPC:**  [a storm cloud](/npc/209160) at this location.



**Signaled to:**  [a storm cloud](/npc/209160)





**AirTrapSpawner despawns.**
end
