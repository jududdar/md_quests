# Maidens Voyage


## On NPC Spawn

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug("Boat spawned! Name is: Maidens Voyage Time is: " .. hour ..":" .. minute .. "", 1);


## Arrive at Waypoint Script

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

if(e.wp == 4) then


**Signaled to:**  [Island Shuttle](/npc/96075)


eq.debug("Boat to firiona (2) has reached the Elf docks. Name is: Maidens Voyage Time is: " .. hour ..":" .. minute .. "", 1);

elseif(e.wp == 5) then


**Signaled to:**  [Island Shuttle](/npc/96075)

elseif(e.wp == 17) then 


eq.debug("Boat to firiona (2) has reached the shuttle. Name is: Maidens Voyage Time is: " .. hour ..":" .. minute .. "", 1);


**Signaled to:**  [Shuttle I](/npc/846)


**Signaled to:**  [Shuttle II](/npc/847)


**Signaled to:**  [Shuttle III](/npc/848)


**Signaled to:**  [Shuttle IV](/npc/849)

elseif(e.wp == 30) then


eq.debug("Boat to firiona (2) has reached its destination! Name is: Maidens Voyage Time is: " .. hour ..":" .. minute .. "", 1);


eq.get_entity_list():ForeachClient(



function(ent)




ent:Signal(1);






function(ent)




local px = ent:GetX();




local py = ent:GetY();




local boat_id = ent:GetBoatID();




local diff_boat_check = boat_id ==  [Island Shuttle](/npc/96075) or boat_id ==  [Shuttle I](/npc/846) or boat_id ==  [Shuttle II](/npc/847) or boat_id ==  [Shuttle III](/npc/848) or boat_id ==  [Shuttle IV](/npc/849);









local valid_pos_check = px >= -3000 and px <= -1700 and py >= 0 and py <= 1800;









if(diff_boat_check and valid_pos_check) then





return true;







return false;




);


eq.get_entity_list():ForeachClient(



function(ent)




ent:MovePC(84,4421,-5685,-67, 0);






function(ent)




if(ent:GetBoatID() == 838) then





return true;







return false;




);
end



## Depart from Waypoint Script

if(e.wp == 5) then





**Signaled to:**  [Glisse Bluesea](/npc/68236)
end
