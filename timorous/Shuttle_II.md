# Shuttle II



[Shuttle II](/npc/847) is a level 50 Launch Warrior that spawns in [Timorous Deep](/zone/96).



## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Boat spawned! Name is: Shuttle II Time is: " .. hour ..":" .. minute .. "", 1);


## Signals

if(e.signal == 1) then


eq.start(17);
end



## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.gridid == 17 and e.wp == 8) then


eq.spawn_condition("butcher",4,1);


eq.spawn_condition("timorous",6,0);


eq.debug("Shuttle to butcher (4) has reached its destination! Name is: Shuttle II Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:Signal(3);






function(ent)




local px = ent:GetX();




local py = ent:GetY();




local boat_id = ent:GetBoatID();




local diff_boat_check = boat_id == 838 or boat_id == 846 or boat_id == 848 or boat_id == 849 or boat_id == 96075;









local valid_pos_check = px >= -7721 and px <= -7503 and py >= 3444 and py <= 3772;









if(diff_boat_check and valid_pos_check) then





return true;







return false;




);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(68, 3595, 452, 19, 0);






function(ent)




local px = ent:GetX();




local py = ent:GetY();









local valid_pos_check = px >= -7721 and px <= -7503 and py >= 3444 and py <= 3772;




if(ent:GetBoatID() == 847 and valid_pos_check) then





return true;







return false;




);
end