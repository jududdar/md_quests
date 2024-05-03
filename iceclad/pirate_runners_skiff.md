# pirate runners skiff


## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Shuttle spawned! Name is: pirate runners skiff Time is: " .. hour ..":" .. minute .. "", 1);


## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.wp == 4) then


eq.debug("Shuttle to nro (2) has reached the docks.  Name is: pirate runners skiff Time is: " .. hour ..":" .. minute .. "", 1);

elseif(e.wp == 9) then


eq.debug("Shuttle to nro (2) has reached its destination! Name is: pirate runners skiff Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(34,-1116,525,-6,0); 






function(ent)




if(ent:GetBoatID() == 843) then





return true;







return false;




);
end