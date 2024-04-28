# player
function event_enter_zone(e)

local qglobals = eq.get_qglobals();



if(e.self:GetBoatID() == 770 or e.self:GetBoatID() == 771) then


**Signaled to:**  [Zachariah Reigh](/npc/69078)

else


**Signaled to:**  [Zachariah Reigh](/npc/69078)



if(qglobals.strongbox ~= nil) then


**Spawns on ground:**  [A Strongbox](/item/13860) at (**y:** -433, **x:** - [Sarnak Battle Shield](/item/9205))


eq.delete_global("strongbox");
end

function event_board_boat(e)

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

local minute = zone_time["zone_minute"];

eq.debug(" At: " .. hour .. ":" .. minute .. " BoatID: " .. e.boat_id .. " was boarded. Its name is: " .. e.self:GetBoatName() .. ".", 1);
function event_leave_boat(e)

local zone_time = eq.get_zone_time();

local hour = zone_time["zone_hour"];

eq.debug(" At: " .. hour .. ":00 I left BoatID: " .. e.boat_id .. ".", 1);
end