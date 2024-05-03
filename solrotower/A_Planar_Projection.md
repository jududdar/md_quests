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






if ( not qglobals.sol_room or qglobals.sol_room ~= "11111" ) then






return;






**You say:** `hail`







if ( qglobals.pofire and qglobals.pofire == "1" and qglobals.zeks and qglobals.zeks == "7" ) then









**Message:** <span class="text-warning">*Miak the Searedsoul's thoughts enter into your own.  'That is it!  The portal into the Plane of Fire lies within the Lava Well of Ro.  You must now fall into this well to gain access into that plane.  I will make adjustments to the Plane of Tranquility portal so that you can access that Element from here as well.'*</span>





eq.set_global("pofire", "2", 5, "F");





**Message:** <span class="text-warning">*You have received a character flag!*</span>





flags = flags + 1;











if ( qglobals.cl_solusek ) then






eq.delete_global("cl_solusek");













elseif ( not qglobals.cl_solusek  ) then




**Message:** <span class="text-warning">*The Planar Projection flickers in and out of existence.  It seems to be impressed by the defeat of Solusek Ro.*</span>




eq.set_global("cl_solusek", "1", 5, "F");




**Message:** <span class="text-warning">*You have received a new checklist flag!*</span>




flags = flags + 1;



end
