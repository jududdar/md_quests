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







if ( not qglobals.bertox_key ) then




return;









local fuirstel = tonumber(qglobals.fuirstel or 0);







if ( fuirstel == 3 ) then




**Message:** <span class="text-warning">*Milyk Fuirstel's thoughts enter into your own.  'Bertoxxulous is slain, for this my brother and I are forever in your debt.  Please, when you have the opportunity come visit me in the Plane of Tranquility.  I would like to thank you face to face.'*</span>




eq.set_global("fuirstel", "4", 5, "F");




**Message:** <span class="text-warning">*You have received a character flag!*</span>




flags = flags + 1;









if ( qglobals.cl_bertox ) then





eq.delete_global("cl_bertox");











elseif ( not qglobals.cl_bertox and fuirstel < 3 ) then




**Message:** <span class="text-warning">*The Planar Projection seems to flicker in and out of existence.  It seems joyous that Bertoxxulous has been slain.*</span>




**Message:** <span class="text-warning">*You have received a new checklist flag!*</span>




eq.set_global("cl_bertox", "1", 5, "F");




flags = flags + 1;






end
