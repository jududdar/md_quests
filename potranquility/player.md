# player





local level_for_tier_two = 55;



local level_for_tier_three = 62;
local level_for_tier_four = 255;
local level_for_elemental = 255;

function event_click_door(e)

local qglobals = eq.get_qglobals(e.self);

local door_id = e.door:GetDoorID();




if(door_id == 16 or door_id == 21) then


if(e.self:GetLevel() >= level_for_tier_two or (qglobals.mavuin and qglobals.mavuin == "3")) then



if(e.self:HasZoneFlag(210) == false or e.self:HasZoneFlag(208) == false) then




e.self:SetZoneFlag(210);




e.self:SetZoneFlag(208);




else



e.self:Message(13, "You lack the will to pass through this portal safely.");

  



if(door_id == 12) then




if ( not e.self:HasZoneFlag(200) ) then






if ( e.self:GetItemIDAt(0) == 9294 and not e.self:KeyRingCheck(9294) ) then




e.self:KeyRingAdd(9294);













if ( e.self:GetLevel() >= level_for_tier_two or e.self:KeyRingCheck(9294) ) then




e.self:SetZoneFlag(200);



else




e.self:Message(13, "You lack the will to pass through this portal safely.");



  



if(door_id == 93) then


if ( e.self:GetItemIDAt(0) == 29213 and not e.self:KeyRingCheck(29213) ) then



e.self:KeyRingAdd(29213);



if(e.self:GetLevel() >= level_for_tier_two or (qglobals.fuirstel and qglobals.fuirstel == "5" and qglobals.thelin and qglobals.thelin == "4") or e.self:KeyRingCheck(29213)) then



if(e.self:HasZoneFlag(207) == false) then




e.self:SetZoneFlag(207);




else



e.self:Message(13, "You lack the will to pass through this portal safely.");

  



if(door_id == 48) then


local karana = tonumber(qglobals.karana or 0);


if(e.self:GetLevel() >= level_for_tier_three or karana >= 3 or qglobals.zebuxoruk) then



if(e.self:HasZoneFlag(209) == false) then




e.self:SetZoneFlag(209);




else



e.self:Message(13, "You lack the will to pass through this portal safely.");





if(door_id == 23) then



if ( not e.self:HasZoneFlag(211) ) then






if ( e.self:GetItemIDAt(0) == 29214 and not e.self:KeyRingCheck(29214) ) then




e.self:KeyRingAdd(29214);












if ( e.self:GetLevel() >= level_for_tier_three or e.self:KeyRingCheck(29214) ) then




e.self:SetZoneFlag(211);



else




e.self:Message(13, "You lack the will to pass through this portal safely.");









if(door_id == 24) then


local zeks = tonumber(qglobals.zeks or 0);


if ( (e.self:GetItemIDAt(0) == 29215 and not e.self:KeyRingCheck(29215) ) ) then



e.self:KeyRingAdd(29215);



if(e.self:GetLevel() >= 60 or zeks >= 2 or e.self:KeyRingCheck(29215)) then



if(e.self:HasZoneFlag(214) == false) then




e.self:SetZoneFlag(214);




else



e.self:Message(13, "You lack the will to pass through this portal safely.");

 
  



if(door_id == 22) then


local zeks = tonumber(qglobals.zeks or 0);


if(e.self:GetLevel() >= level_for_tier_four or (qglobals.cipher and zeks >= 6)) then



if(e.self:HasZoneFlag(212) == false) then




e.self:SetZoneFlag(212);




else



e.self:Message(13, "You lack the will to pass through this portal safely.");

  



if(door_id == 82) then



if ( not e.self:HasZoneFlag(217) ) then










if ( e.self:GetLevel() >= level_for_elemental ) then




e.self:SetZoneFlag(217);



else







e.self:Message(13, "You lack the will to pass through this portal safely.");







if(door_id == 81 or door_id == 83 or door_id == 84) then


if(e.self:GetLevel() >= level_for_elemental or (qglobals.zebuxoruk and qglobals.zebuxoruk == "2")) then



if(e.self:HasZoneFlag(216) == false or e.self:HasZoneFlag(215) == false or e.self:HasZoneFlag(218) == false) then




e.self:SetZoneFlag(216);




e.self:SetZoneFlag(215);




e.self:SetZoneFlag(218);




else



e.self:Message(13, "You lack the will to pass through this portal safely.");





if(door_id == 18) then





if ( e.self:GetGM() or ( e.self:GetLevel() >= 65 and e.self:HasZoneFlag(219) and qglobals.time ) ) then



e.self:Message(0, "The ages begin to tear through your body.  You wake to find yourself in another time.");






else



e.self:Message(13, "You lack the will to pass through this portal safely.");

end
