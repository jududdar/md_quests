# Golden Maiden
## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Boat spawned! Name is: " .. e.self:GetName() .. " Time is: " .. hour ..":" .. minute .. "", 1);

## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.wp == 12) then


eq.debug("Boat to Erudsxing has reached its destination! Name is: " .. e.self:GetName() .. " Time is: " .. hour ..":" .. minute .. "", 1);


eq.spawn_condition("qeynos",3,0);


eq.spawn_condition("qeynos",4,0);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(98,-2190,-464,-22,64);






function(ent)




if(ent:GetBoatID() == 773) then





return true;







return false;




);
end