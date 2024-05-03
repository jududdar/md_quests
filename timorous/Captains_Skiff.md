# Captains Skiff


## Signals 



if(e.signal == 1) then 


 

eq.start(4);

 

## Arrive at Waypoint Script
 
local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.wp == 2) then


eq.stop();


eq.debug("Shuttle to butcherblock (4) has reached its destination! Name is: Captains Skiff Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:Signal(2);






function(ent)









if(ent:GetBoatID() == 838 and ent:GetX() < -7100) then





return true;







return false;




);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(68,3658,476,-13, 0);






function(ent)




if(ent:GetBoatID() == 842) then





return true;







return false;




);
end