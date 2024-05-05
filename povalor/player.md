# player





function event_click_door(e)

local door_id = e.door:GetDoorID();

local adUp = **spawned NPC:**  [\#Aerin\`Dar](/npc/208074); 




if ( door_id == 3 ) then




local qglobals = eq.get_qglobals(e.self);



if ( qglobals.aerindar and qglobals.aerindar == "2" ) then



return;






if ( not qglobals.aerindar ) then



e.self:Message(13, "You lack the will to pass through this portal safely.");


else



eq.set_global("aerindar", "2", 5, "F");



e.self:Message(15, "You have received a character flag!");







if ( qglobals.cl_aerindar ) then




eq.delete_global("cl_aerindar");






if ( e.self:HasZoneFlag(211) == false ) then




e.self:SetZoneFlag(211);









elseif ( door_id == 6 and adUp ) then




e.self:MovePC(208, 352, 2172, 33, 0);


if ( e.self:GetPet().valid and not e.self:GetPet():Charmed() ) then



e.self:GetPet():GMMove(352, 2172, 33, 0);







elseif ( door_id == 8 or door_id == 9 ) then





if ( e.self:GetItemIDAt(0) == 25596 ) then 



local door = eq.get_entity_list():GetDoorsByDoorID(2);



door:ForceOpen(e.self);



e.door:ForceOpen(e.self);







elseif ( door_id == 11 and not adUp ) then


e.door:ForceOpen(e.self);



end
