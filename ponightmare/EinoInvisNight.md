# EinoInvisNight
local EINO_TYPE = 204467; 

## On NPC Spawn

eq.debug("EinoInvisNight spawn", 2);

local xloc = e.self:GetX();

local yloc = e.self:GetY();

eq.set_proximity(xloc - 30, xloc + 30, yloc - 30, yloc + 30);

eq.enable_proximity_say();


**Set a timer** named *timecheck* for 10 seconds
## Timer(s)


if ( e.timer == "timecheck" ) then


local zoneTime = eq.get_zone_time()["zone_hour"];


if ( zoneTime > 6 and zoneTime < 20 ) then



**EinoInvisNight despawns.**



eq.debug("EinoInvisNight despawn", 2);

end

function event_proximity_say(e)



**You say:** `Quellious be my guide`



eq.unique_spawn(EINO_TYPE, 8, 0, 1686, -527, 217.194, 37);


**EinoInvisNight despawns.**
end

