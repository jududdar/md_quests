# Shuttle II


## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Boat spawned! Name is: Shuttle II Time is: " .. hour ..":" .. minute .. "", 1);

eq.start(21);


## Signals

if(e.signal == 1) then


eq.start(17);
end



## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.gridid == 21 and e.wp == 11) then


eq.stop();


eq.move_to(3158, 834, -13, 65.27, true);

if(e.gridid == 17 and e.wp == 12) then


eq.spawn_condition("butcher",4,0);


eq.spawn_condition("timorous",6,1);


eq.debug("Shuttle to timorous (4) has reached its destination! Name is: Shuttle II Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:Signal(2);






function(ent)




local px = ent:GetX();




local py = ent:GetY();




local boat_id = ent:GetBoatID();




local diff_boat_check = boat_id == 846 or boat_id == 848 or boat_id == 849;









local valid_pos_check = px >= 3567 and px <= 3655 and py >= 440 and py <= 464;









if(diff_boat_check and valid_pos_check) then





return true;







return false;




);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(96, -7580, 3580, 19, 144);






function(ent)




local px = ent:GetX();




local py = ent:GetY();









local valid_pos_check = px >= 3567 and px <= 3655 and py >= 440 and py <= 464;




if(ent:GetBoatID() == 847 and valid_pos_check) then





return true;







return false;




);
end