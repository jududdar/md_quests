# A Planar Projection
local MAX_KEYS = 54;

local keys;
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

**Set a timer** named *depop* for 600 seconds

keys = 0;


## Timer(s)

**A Planar Projection despawns.**


## Combat

if  A Planar Projection enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## Dialog

local qglobals = eq.get_qglobals(e.other);


if ( ClientCanFlag(e.other) ) then



**You say:** `hail`







if ( not qglobals.earthb_key and keys < MAX_KEYS ) then





>**A Planar Projection says:** Your will must be strong Soandso. Seek council with the council of twelve if you so wish.




eq.set_global("earthb_key", "1", 5, "F");




**Message:** <span class="text-warning">*You have received a character flag!*</span>





keys = keys + 1;




if ( keys == MAX_KEYS ) then





**A Planar Projection despawns.**






end
