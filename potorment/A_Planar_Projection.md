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







if ( qglobals.tylis and qglobals.tylis == "2" ) then









**Message:** <span class="text-warning">*The Planar Projection's thoughts enter your own.  'You have done well, now receive the knowledge that Saryrn once held!'  You look down at your arms to see a set of unintelligible runes being burnt into your arms.  The pain is terrible and searing.  Suddenly the sensation is gone and the runes slowly fade.*</span>





eq.set_global("saryrn", "1", 5, "F");





**Message:** <span class="text-warning">*You have received a character flag!*</span>





flags = flags + 1;











if ( qglobals.cl_saryrn ) then






eq.delete_global("cl_saryrn");













elseif ( not qglobals.cl_saryrn  ) then




**Message:** <span class="text-warning">*The Planar Projection seems to flicker in and out of existence.  It seems to be impressed and grateful for the death of Saryrn.*</span>




eq.set_global("cl_saryrn", "1", 5, "F");




**Message:** <span class="text-warning">*You have received a new checklist flag!*</span>




flags = flags + 1;



end
