# pirate runners skiff



[pirate runners skiff](/npc/843) is a level 60 Launch Warrior that spawns in [Northern Desert of Ro](/zone/34).



## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Shuttle spawned! Name is: pirate runners skiff Time is: " .. hour ..":" .. minute .. "", 1);


## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.wp == 6) then


eq.debug("Shuttle to iceclad (3) has reached the docks.  Name is: pirate runners skiff Time is: " .. hour ..":" .. minute .. "", 1);

elseif(e.wp == 13) then


eq.debug("Shuttle to iceclad (3) has reached its destination! Name is: pirate runners skiff Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(110,-23000,3556,-40,0); 






function(ent)




if(ent:GetBoatID() == 843) then





return true;







return false;




);
end