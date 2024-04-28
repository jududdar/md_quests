# player
function event_click_door(e)

local door_id = e.door:GetDoorID();


if ( door_id == 2 or door_id == 166 ) then 


if ( not e.self:KeyRingCheck(20033) and e.self:HasItem(20033) ) then



e.self:KeyRingAdd(20033);



if( e.self:KeyRingCheck(20033) ) then



MoveGroup(e.self:GetGroup(),e.self, e.self:GetX(), e.self:GetY(), e.self:GetZ(), 75, 660, 100, 40, 0);


elseif ( door_id == 4 or door_id == 167 ) then 


if ( not e.self:KeyRingCheck(20034) and e.self:HasItem(20034) ) then



e.self:KeyRingAdd(20034);



if( e.self:KeyRingCheck(20034) ) then



MoveGroup(e.self:GetGroup(),e.self, e.self:GetX(), e.self:GetY(), e.self:GetZ(), 75, 670, 750, 75, 0);


elseif ( door_id == 16 or door_id == 165 ) then 


if ( not e.self:KeyRingCheck(20035) and e.self:HasItem(20035) ) then



e.self:KeyRingAdd(20035);



if ( e.self:KeyRingCheck(20035) )  then
 


MoveGroup(e.self:GetGroup(),e.self, e.self:GetX(), e.self:GetY(), e.self:GetZ(), 75, 170, 755, 175, 0);


elseif ( door_id == 27 or door_id == 169 ) then 


if ( not e.self:KeyRingCheck(20036) and e.self:HasItem(20036) ) then



e.self:KeyRingAdd(20036);



if( e.self:KeyRingCheck(20036)  ) then
 


MoveGroup(e.self:GetGroup(),e.self, e.self:GetX(), e.self:GetY(), e.self:GetZ(), 75, -150, 160, 217, 0);


elseif ( door_id == 34 or door_id == 168 ) then 


if ( not e.self:KeyRingCheck(20037) and e.self:HasItem(20037)  ) then



e.self:KeyRingAdd(20037);



if( e.self:KeyRingCheck(20037) ) then
 


MoveGroup(e.self:GetGroup(),e.self, e.self:GetX(), e.self:GetY(), e.self:GetZ(), 75, -320, 725, 12, 0);


elseif ( door_id == 154 ) then 


if ( not e.self:KeyRingCheck(20038) and e.self:HasItem(20038)  ) then



e.self:KeyRingAdd(20038);



if( e.self:KeyRingCheck(20038) ) then
 


MoveGroup(e.self:GetGroup(),e.self, e.self:GetX(), e.self:GetY(), e.self:GetZ(), 75, 10, 65, 310, 0);


elseif ( door_id == 1 ) then 


if ( not e.self:KeyRingCheck(20039) and e.self:HasItem(20039) ) then



e.self:KeyRingAdd(20039);



if( e.self:KeyRingCheck(20039) ) then
 


MoveGroup(e.self:GetGroup(),e.self, e.self:GetX(), e.self:GetY(), e.self:GetZ(), 75, 20, 250, 355, 0);

end

function MoveGroup(frozen_group, player, src_x, src_y, src_z, distance, tgt_x, tgt_y, tgt_z, tgt_h)

if ( frozen_group.valid ) then


local frozen_count = frozen_group:GroupCount();



for i = 0, frozen_count - 1, 1 do



local client_v = frozen_group:GetMember(i):CastToClient();






if (client_v.valid) then









if (client_v:CalculateDistance(src_x, src_y, src_z) <= distance) then











client_v:MovePC(111, tgt_x, tgt_y, tgt_z, tgt_h); 







else


player:MovePC(111, tgt_x, tgt_y, tgt_z, tgt_h); 
end
