# Stop Cheating
local BAD_COORDS = {



{ -1000, 670,



  -1000, 1000,



  254, 1000,



},



{ -166, 900,



  -640, 640,



  -200, -1,




},



{ 375, 750,



  500, 640,



  -1000, 1000,



},



{ 365, 750,



  -640, -500,



  -1000, 1000,



},
};

local cheaters = {};
local cheatersToSlay = false;



## On NPC Spawn

**Set a timer** named *check* for 10 seconds


## Signals

table.insert(cheaters, e.signal);

if ( not cheatersToSlay ) then


**Set a timer** named *kill_list* for 0 seconds

cheatersToSlay = true;
eq.debug(tostring(e.signal));


## Timer(s)

if ( e.timer == "kill_list" ) then


local i = #cheaters;


local client;


if ( i > 0 ) then





client = eq.get_entity_list():GetClientByID(cheaters[i]);



if ( client and client.valid ) then








if ( client:GetX() > 1366 and e.self:GetX() < 1000 ) then 





e.self:GMMove(1092, 0, 235, 64);





return;







e.self:CastSpell(982, client:GetID(), 0, 100); 





table.remove(cheaters, i);




elseif ( e.timer == "check" ) then


local clientList = eq.get_entity_list():GetClientList();



if ( clientList ) then



for client in clientList.entries do








if ( not client:GetGM() ) then





for _, coords in ipairs(BAD_COORDS) do












if ( client:GetX() > coords[1] and client:GetX() < coords[2]







and client:GetY() > coords[3] and client:GetY() < coords[4]







and client:GetZ() > coords[5] and client:GetZ() < coords[6]






) then







e.self:CastSpell(982, client:GetID(), 0, 100); 







return;




















if ( cheatersToSlay and #cheaters == 0 ) then



**Stop timer** named *kill_list*



cheatersToSlay = false;



if ( e.self:GetX() > 500 ) then




e.self:GMMove(500, 0, 255, 0);



end
