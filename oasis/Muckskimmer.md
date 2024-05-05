# Muckskimmer



[Muckskimmer](/npc/841) is a level 50 Launch Warrior that spawns in [Oasis of Marr](/zone/37).



## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Shuttle spawned! Name is: Muckskimmer Time is: " .. hour ..":" .. minute .. "", 1);


## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.wp == 5) then


eq.debug("Shuttle to timorous (1) has reached the docks.  Name is: Muckskimmer Time is: " .. hour ..":" .. minute .. "", 1);

elseif(e.wp == 11) then


eq.debug("Shuttle to timorous (1) has reached its destination! Name is: Muckskimmer Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(96,5359,7581,-2,0);






function(ent)




if(ent:GetBoatID() == 841) then





return true;







return false;




);
end