# Shuttle I
## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Boat spawned! Name is: Shuttle I Time is: " .. hour ..":" .. minute .. "", 1);
## Signals

if(e.signal == 1) then


eq.start(16);
end

## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.gridid == 16 and e.wp == 3) then


eq.spawn_condition("butcher",3,1);


eq.spawn_condition("timorous",5,0);


eq.debug("Shuttle to butcher (4) has reached its destination! Name is: Shuttle I Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:Signal(2);






function(ent)




local px = ent:GetX();




local py = ent:GetY();




local boat_id = ent:GetBoatID();




local diff_boat_check = boat_id == 838 or boat_id == 847 or boat_id == 848 or boat_id == 849 or boat_id == 96075;









local valid_pos_check = px >= -7721 and px <= -7503 and py >= 3444 and py <= 3772;









if(diff_boat_check and valid_pos_check) then





return true;







return false;




);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(68, 3595, 491, 19, 0);






function(ent)




local px = ent:GetX();




local py = ent:GetY();









local valid_pos_check = px >= -7721 and px <= -7503 and py >= 3444 and py <= 3772;




if(ent:GetBoatID() == 846 and valid_pos_check) then





return true;







return false;




);
end