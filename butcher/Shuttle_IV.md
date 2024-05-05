# Shuttle IV



[Shuttle IV](/npc/849) is a level 50 Launch Warrior that spawns in [Butcherblock Mountains](/zone/68).



## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Boat spawned! Name is: Shuttle IV Time is: " .. hour ..":" .. minute .. "", 1);

eq.start(23);


## Signals

if(e.signal == 1) then


eq.start(19);
end



## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.gridid == 23 and e.wp == 11) then


eq.stop();


eq.move_to(3067, 879, -12, 65.27, true);

if(e.gridid == 19 and e.wp == 12) then


eq.spawn_condition("butcher",6,0);


eq.spawn_condition("timorous",8,1);


eq.debug("Shuttle to timorous (4) has reached its destination! Name is: Shuttle IV Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:Signal(4);






function(ent)




local px = ent:GetX();




local py = ent:GetY();




local boat_id = ent:GetBoatID();




local diff_boat_check = boat_id == 846 or boat_id == 847 or boat_id == 848;









local valid_pos_check = px >= 3567 and px <= 3655 and py >= 520 and py <= 544;









if(diff_boat_check and valid_pos_check) then





return true;







return false;




);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(96, -7680, 3620, 19, 144);






function(ent)




local px = ent:GetX();




local py = ent:GetY();









local valid_pos_check = px >= 3567 and px <= 3655 and py >= 520 and py <= 544;




if(ent:GetBoatID() == 849 and valid_pos_check) then





return true;







return false;




);
end