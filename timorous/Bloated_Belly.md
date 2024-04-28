# Bloated Belly
## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Boat spawned! Name is: Bloated Belly Time is: " .. hour ..":" .. minute .. "", 1);
## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.wp == 40) then


eq.debug("Boat to overthere (15) has reached the docks. Name is: Bloated Belly Time is: " .. hour ..":" .. minute .. "", 1);

elseif(e.wp == 65) then


eq.debug("Boat to overthere (15) has reached its destination! Name is: Bloated Belly Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(93,1589,4846,-161, 0);






function(ent)




if(ent:GetBoatID() == 839) then





return true;







return false;




);
end