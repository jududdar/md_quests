# Tarkil Adan
local MAX_KEYS = 36;

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

**Tarkil Adan despawns.**
## Combat

if  Tarkil Adan enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end

## Dialog

local qglobals = eq.get_qglobals(e.other);


if ( ClientCanFlag(e.other) ) then



**You say:** `hail`







if ( not qglobals.bertox_key and keys < MAX_KEYS ) then





**Message:** <span class="text-warning">*Tarkil Adan lets out a groan and then whimpers saying, 'Yes great ones yesss I was king once I wasss. ' The creature then mutters under his breath and passes you a small glowing bone fragment etched in runes. Then speaks again saying, 'The tortured ones oh the tortured ones, you must go to the depths of Lxanvom and free them.  Go to the bone throne at the ruins entrance there you will find access to the depths.'  He then goes back to whimpering and rocking back and forth.*</span>




eq.set_global("bertox_key", "1", 5, "F");




**Message:** <span class="text-warning">*You have received a character flag!*</span>





keys = keys + 1;



end
