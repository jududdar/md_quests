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







if ( not qglobals.aerindar and qglobals.mavuin and qglobals.mavuin == "3" and flags < FLAG_LIMIT ) then




**Message:** <span class="text-warning">*The Planar Projection's thoughts enter your own.  'You have done well. You will now be able to enter the Halls of Honor.'*</span>




eq.set_global("aerindar", "1", 5, "F");














flags = flags + 1;



end
