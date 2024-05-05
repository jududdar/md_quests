# player





function event_click_door(e)

local door_id = e.door:GetDoorID();

local entity_list = eq.get_entity_list();




if(door_id == 5) then


OpenDoors(e,entity_list,door_id,7,9);
end

function OpenDoors(e, entity_list, door_id, first_id, last_id)

for i = first_id, last_id, 1 do








if (door_id ~= i) then



entity_list:FindDoor(i):ForceOpen(e.self);

end