# Maidens Voyage



[Maidens Voyage](/npc/838) is a level 50 Ship Warrior that spawns in [Firiona Vie](/zone/84).



## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Boat spawned! Name is: Maidens Voyage Time is: " .. hour ..":" .. minute .. "", 1);


## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.wp == 12) then


eq.debug("Boat to timorous (18) has reached the docks.  Name is: Maidens Voyage Time is: " .. hour ..":" .. minute .. "", 1);

elseif(e.wp == 17) then


eq.debug("Boat to timorous (18) has reached waypoint 17.  Name is: Maidens Voyage Time is: " .. hour ..":" .. minute .. "", 1);

elseif(e.wp == 18) then


eq.debug("Boat to timorous (18) has reached its destination! Name is: Maidens Voyage Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(96,-2098,-2260,57,17);






function(ent)




if(ent:GetBoatID() == 838) then





return true;







return false;




);
end



## Depart from Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.wp == 12) then


eq.debug("Boat to timorous (18) has departed the docks. Name is: Maidens Voyage Time is: " .. hour ..":" .. minute .. "", 1);





**Signaled to:**  [Glisse Bluesea](/npc/68236)
end