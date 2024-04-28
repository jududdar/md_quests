# A Planar Projection




local FLAG_LIMIT = 72 * 2;

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



if ( ClientCanFlag(e.other) and flags <= FLAG_LIMIT ) then



**You say:** `hail`







if ( qglobals.fuirstel ) then




if ( qglobals.fuirstel == "1" ) then





**Message:** <span class="text-warning">*You recognize the sound of the voice echoing in your mind to be Milyk Fuirstel's.  He tells you before fading, 'I beg of you, return to me with the ward that now envelops your body.  This etheric energy is the only thing that can stop this plague that has been placed upon me.'*</span>





eq.set_global("fuirstel", "2", 5, "F");





**Message:** <span class="text-warning">*You have received a character flag!*</span>





flags = flags + 1;











if ( qglobals.cl_grummus ) then






eq.delete_global("cl_grummus");













else




if ( not qglobals.cl_grummus ) then





**Message:** <span class="text-warning">*The Planar Projection tells you, 'Now that Grummus has fallen, you must pass into the plane of Bertoxxulous. Deep inside of this castle you will find a room with a large decaying pipe. Push it out of the way and jump into the very plague that is Bertoxxulous' home. Be wary in your travels, for his pestilence shall consume you.'*</span>





eq.set_global("cl_grummus", "1", 5, "F");





**Message:** <span class="text-warning">*You have received a new checklist flag!*</span>





flags = flags + 1;












if ( not qglobals.grummus ) then




eq.set_global("grummus", "1", 5, "F");




flags = flags + 1;



end
