# Golden Maiden



[Golden Maiden](/npc/773) is a level 50 Ship Warrior that spawns in [Erudin](/zone/24).



## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Boat spawned! Name is: Golden Maiden Time is: " .. hour ..":" .. minute .. "", 1);



## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.wp == 7) then


**Signaled to:**  [Sabrina](/npc/24056)

elseif(e.wp == 8) then


**Signaled to:**  [Sabrina](/npc/24056)


**Signaled to:**  [Reko Saltamer](/npc/24085)

elseif(e.wp == 10) then


eq.debug("Boat to Erudsxing has reached its destination! Name is: Golden Maiden Time is: " .. hour ..":" .. minute .. "", 1);


eq.spawn_condition("erudnext",1,0);


eq.spawn_condition("erudnext",2,0);


eq.get_entity_list():ForeachClient(



function(ent)




ent:Signal(2);






function(ent)









if(ent:GetBoatID() ==  [Sabrina](/npc/24056) and ent:GetY() > 500) then





return true;







return false;




);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(98,2337,418,-22,-1);






function(ent)




if(ent:GetBoatID() == 773 and ent:GetY() > 500) then





return true;







return false;




);
end