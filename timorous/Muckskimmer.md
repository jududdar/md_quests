# Muckskimmer



[Muckskimmer](/npc/841) is a level 50 Launch Warrior that spawns in [Timorous Deep](/zone/96).



## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Shuttle spawned! Name is: Muckskimmer Time is: " .. hour ..":" .. minute .. "", 1);


## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.wp == 22) then


eq.debug("Shuttle to oasis (5) has reached the island.  Name is: Muckskimmer Time is: " .. hour ..":" .. minute .. "", 1);

elseif(e.wp == 49) then


eq.debug("Shuttle to oasis (5) has reached its destination! Name is: Muckskimmer Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(37,-1185,1568,-4,0);






function(ent)




if(ent:GetBoatID() == 841) then





return true;







return false;




);
end