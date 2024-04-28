# Sea King
## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Boat spawned! Name is: " .. e.self:GetName() .. " Time is: " .. hour ..":" .. minute .. "", 1);
## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];



if(e.self:GetGrid() == 5 and e.wp == 3) then


eq.debug("Boat to Qeynos (5) has reached its destination! Name is: " .. e.self:GetName() .. " Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(1,775,260,22,192);






function(ent)




if(ent:GetBoatID() == 772) then





return true;







return false;




);



elseif(e.self:GetGrid() == 7 and e.wp == 20) then


eq.debug("Boat to Erud (7) has reached its destination! Name is: " .. e.self:GetName() .. " Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(24,-1606,-584,0,-1);






function(ent)




if(ent:GetBoatID() == 772) then





return true;







return false;




);
end