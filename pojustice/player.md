# player





local SEVENTH_HAMMER_TYPE = 201074;

function event_enter_zone(e)

if ( (e.self:GetY() < -900 and e.self:GetX() > -300) or (e.self:GetY() < -600 and e.self:GetX() > 700) ) then





e.self:MovePC(201, 473, 685, 10, 0); 
end



## Timer(s)

if ( e.timer == "seventh" ) then


**Stop timer** named *seventh*




if ( eq.get_entity_list():IsMobSpawnedByNpcTypeID(SEVENTH_HAMMER_TYPE) ) then



if ( eq.get_entity_list():GetNPCByNPCTypeID(SEVENTH_HAMMER_TYPE):IsEngaged() ) then




return;





e.self:MovePC(201, 76, 1310, 10, 256); 
end

function event_click_door(e)

local id = e.door:GetDoorID();


if ( id >= 1 and id <= 6 and e.self:GetItemIDAt(0) == 31599 ) then




**Set a timer** named *seventh* for 0 seconds
end
