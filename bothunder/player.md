# player




local raids = {};
local gargs = 0;


function FindRaid(e)

local myRaid = e.self:GetRaid();

local myGroup = e.self:GetGroup();

local rid, gid = 0, 0;

local now = eq.clock();



if ( myRaid.valid ) then


rid = myRaid:GetID();

elseif ( myGroup.valid ) then


gid = myGroup:GetID();


for i, raid in ipairs(raids) do



if ( rid > 0 and raid.rid == rid and now < raid.expire ) then



return i;






elseif ( gid > 0 and raid.gid == gid and now < raid.expire ) then



return i;




return nil;
function AddRaid(e)

local myRaid = e.self:GetRaid();

local myGroup = e.self:GetGroup();

local rid, gid = 0, 0;

local idx = FindRaid(e);

local now = eq.clock();



if ( myRaid.valid ) then


rid = myRaid:GetID();

elseif ( myGroup.valid ) then


gid = myGroup:GetID();


if ( idx ) then


raids[idx].expire = now + 60;

else


if ( rid > 0 ) then



eq.debug("Raid ID "..rid.." may now enter Agnarr's tower for the next 60 seconds");



table.insert(raids, { ["rid"] = rid, ["gid"] = 0, ["expire"] = now+60 });



idx = #raids;


elseif ( gid > 0 ) then



eq.debug("Group ID "..gid.." may now enter Agnarr's tower for the next 60 seconds");



table.insert(raids, { ["rid"] = 0, ["gid"] = gid, ["expire"] = now+60 });



idx = #raids;






local i = #raids;

while ( i > 0 ) do


if ( raids[i].expire < now ) then



table.remove(raids, i);





i = i - 1;



return idx;
function AggroGargoyles(player, door_id)


if ( door_id and door_id == 51 ) then



gargs = gargs + 1;





if ( gargs == 1 ) then



player:Message(13, "Magical energies shoot through your body.");



return;


elseif ( gargs == 2 ) then



player:Message(13, "You hear the cracking of stones around you.");



return;


else



gargs = 0;




**Signaled to:**  [A storm watcher](/npc/209113)
function MoveGroup(zone, client, dist, x, y, z, h)

local group = client:GetGroup();

local raid = client:GetRaid();


if ( group and group:GroupCount() > 0 ) then


for i = 0, 5 do



local member = group:GetMember(i):CastToClient();




if ( member.valid ) then




if ( member:CalculateDistance(client:GetX(), client:GetY(), client:GetZ()) < dist ) then





member:MovePC(zone, x, y, z, h*2);





if ( member:GetPet().valid ) then






if ( member:GetPet():Charmed() ) then







member:GetPet():BuffFadeByEffect(22); 






else







member:GetPet():GMMove(x, y, z, 0);














eq.get_entity_list():RemoveFromHateLists(member);










elseif ( raid and raid.valid ) then


local raidGroupID = raid:GetGroup(client:GetName());


local member;


for i = 0, 71 do



member = raid:GetMember(i);







if ( member and member.valid and raid:GetGroup(member:GetName()) == raidGroupID ) then








if ( member:CalculateDistance(client:GetX(), client:GetY(), client:GetZ()) < dist ) then





member:MovePC(zone, x, y, z, h*2);





if ( member:GetPet().valid ) then






if ( member:GetPet():Charmed() ) then







member:GetPet():BuffFadeByEffect(22); 






else







member:GetPet():GMMove(x, y, z, 0);














eq.get_entity_list():RemoveFromHateLists(member);









else


client:MovePC(zone, x, y, z, h*2);





if ( client:GetPet().valid ) then



if ( client:GetPet():Charmed() ) then




client:GetPet():BuffFadeByEffect(22); 



else




client:GetPet():GMMove(x, y, z, 0);





eq.get_entity_list():RemoveFromHateLists(client);
end

function event_click_door(e)


local door_id = e.door:GetDoorID();


if ( door_id == 51 ) then





if ( e.self:GetItemIDAt(0) == 9433 ) then



AddRaid(e);






if ( FindRaid(e) or e.self:GetItemIDAt(0) == 9433 or e.self:GetGM() ) then



e.self:MovePC(209, -765, -1735, 1270, 192*2);







if ( e.self:GetPet().valid ) then




if ( e.self:GetPet():Charmed() ) then





e.self:GetPet():BuffFadeByEffect(22); 




else





e.self:GetPet():GMMove(-765, -1735, 1270, 0);








eq.get_entity_list():RemoveFromHateLists(e.self);






else



AggroGargoyles(e.self, door_id);



elseif ( door_id == 61 ) then





if ( e.self:GetItemIDAt(0) == 9425 or e.self:GetGM() ) then



MoveGroup(209, e.self, 100, 85, 145, 635, 64)





elseif ( door_id == 63 ) then





if ( e.self:GetItemIDAt(0) == 9425 or e.self:GetGM() ) then



MoveGroup(209, e.self, 100, -830, -865, 1375, 64)





elseif ( door_id == 65 ) then




if ( e.self:GetItemIDAt(0) == 9425 or e.self:GetGM() ) then



MoveGroup(209, e.self, 100, -350, -2200, 1955, 128)





elseif ( door_id == 67 ) then




if ( e.self:GetItemIDAt(0) == 9425 or e.self:GetGM() ) then



MoveGroup(209, e.self, 100, 150, -1220, 1120, 64)

end

function event_click_merchant(e)


if ( e.merchant_type_id == 209158 ) then 




e.self:MovePC(209, -665, -1735, 2251, 192*2);


if ( e.self:GetPet().valid and not e.self:GetPet():Charmed() ) then



e.self:GetPet():GMMove(-665, -1735, 2251, 0);

end
