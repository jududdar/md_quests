# player





function event_enter_zone(e)

if(e.self:GetBoatID() == 770 or e.self:GetBoatID() == 771) then


**Signaled to:**  [Olunea Miltin](/npc/10016)

else


**Signaled to:**  [Olunea Miltin](/npc/10016)
end

function event_board_boat(e)

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug(" At: " .. hour .. ":" .. minute .. " BoatID: " .. e.boat_id .. " was boarded. Its name is: " .. e.self:GetBoatName() .. ".", 1);
function event_leave_boat(e)

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug(" At: " .. hour .. ":" .. minute .. " I left BoatID: " .. e.boat_id .. ".", 1);
end