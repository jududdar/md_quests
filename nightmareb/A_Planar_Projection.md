# A Planar Projection
local FLAG_LIMIT = 72;

local flags = 0;
local rid, gid, cid;

function ClientCanFlag(mob)

if ( mob:IsClient() ) then


local client = mob:CastToClient();





local raid = client:GetRaid();


local group = client:GetGroup();





if ( rid and raid.valid and raid:GetID() == rid ) then



return true;


elseif ( gid and group.valid and group:GetID() == gid ) then



return true;


elseif ( cid and client:GetID() == cid ) then



return true;


return false;
## Signals

rid, gid, cid = nil, nil, nil;

local client = eq.get_entity_list():GetClientByID(e.signal);




if ( client.valid ) then




local raid = client:GetRaid();


local group = client:GetGroup();





if ( raid.valid ) then



rid = raid:GetID();


elseif ( group.valid ) then



gid = group:GetID();


else



cid = client:GetID();



eq.debug("Flagger NPC will acknowledge "..client:GetName().."'s raid/group; Raid ID == "..(rid or "(nil)")..";  Group ID == "..(gid or "(nil)"), 1);
end

## On NPC Spawn

flags = 0;

**Set a timer** named *depop* for 600 seconds
## Timer(s)

if ( e.timer == "depop" ) then


**A Planar Projection despawns.**
end

## Dialog

local qglobals = eq.get_qglobals(e.other);



if ( ClientCanFlag(e.other) ) then



**You say:** `hail`







if ( qglobals.thelin ) then




if ( qglobals.thelin == "2" and flags < FLAG_LIMIT ) then





**Message:** <span class="text-warning">*You recognize the voice in your mind to be Thelin Poxbourne's.  The words echo, 'The cruel hand of Terris no longer shall torment my dreams.  Thank you friends, you are my savior.  Please return to me in the Plane of Tranquility.  I would like to express to you my gratitude.'*</span>





eq.set_global("thelin", "3", 5, "F");





**Message:** <span class="text-warning">*You have received a character flag!*</span>





flags = flags + 1;











if ( qglobals.cl_terris ) then






eq.delete_global("cl_terris");










elseif ( not qglobals.thelin or qglobals.thelin == "1" ) then




if ( not qglobals.cl_terris and flags <= FLAG_LIMIT ) then











eq.set_global("cl_terris", "1", 5, "F");





**Message:** <span class="text-warning">*You have received a new checklist flag!*</span>





flags = flags + 1;






end
