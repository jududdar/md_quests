# SirensBane



[SirensBane](/npc/771) is a level 50 Ship Warrior that spawns in [East Freeport](/zone/10).



## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Boat spawned! Name is: SirensBane Time is: " .. hour ..":" .. minute .. "", 1);


## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.wp == 9) then


eq.debug("Boat to OOT has reached its destination! Name is: SirensBane Time is: " .. hour ..":" .. minute .. "", 1);


eq.spawn_condition("freporte",3,0);


eq.spawn_condition("freporte",4,0);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(69,-10607,-2995,20,0);






function(ent)




if(ent:GetBoatID() == 771) then





return true;







return false;




);
end