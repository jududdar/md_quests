# Stormbreaker


## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Boat spawned! Name is: Stormbreaker Time is: " .. hour ..":" .. minute .. "", 1);



## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];



if(e.self:GetGrid() == 60 and e.wp == 18) then


eq.debug("Boat to Freeport (60) has reached its destination! Name is: Stormbreaker Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(10,-1853,-748,-80,0); 






function(ent)




if(ent:GetBoatID() == 770) then





return true;







return false;




);



elseif(e.self:GetGrid() == 61 and e.wp == 16) then


eq.debug("Boat to Butcher (61) has reached its destination! Name is: Stormbreaker Time is: " .. hour ..":" .. minute .. "", 1);











eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(68,4591,2090,-15,0);






function(ent)




if(ent:GetBoatID() == 770) then





return true;







return false;




);
end