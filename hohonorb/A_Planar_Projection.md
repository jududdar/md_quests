# A Planar Projection



[A Planar Projection](/npc/200269) is a level 1 Elemental Warrior that spawns in [Temple of Marr](/zone/220).

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



**You say:** `hail`




if ( not qglobals.mmarr and not qglobals.cipher ) then






if ( qglobals.hohtrials and qglobals.hohtrials == "111" ) then




**Message:** <span class="text-warning">*The Planar Projection's thoughts enter your own.  'You have done well, now receive the knowledge that Mithaniel Marr once held!'  You look down at your arms to see a set of unintelligible runes being burnt into your arms.  The pain is terrible and searing.  Suddenly the sensation is gone and the runes slowly fade.  Also among your possessions you find a small tattered book as old as the ages.  You recognize it as something that Maelin might be able to translate.*</span>




eq.set_global("mmarr", "1", 5, "F");




**Message:** <span class="text-warning">*You have received a character flag!*</span>




flags = flags + 1;









if ( qglobals.cl_mmarr ) then





eq.delete_global("cl_mmarr");






else




**Message:** <span class="text-warning">*The Planar Projection's thoughts enter your own.  'You have done well, however you are not ready to understand the Knowledge gained for defeating Mithaniel Marr.  Once you have learned more this knowledge will be revealed to you.'*</span>




eq.set_global("cl_mmarr", "1", 5, "F");




**Message:** <span class="text-warning">*You have received a new checklist flag!*</span>




flags = flags + 1;








if ( not qglobals.zebuxoruk and not qglobals.mmarr_book ) then






if ( qglobals.hohtrials and qglobals.hohtrials == "111" ) then




eq.set_global("mmarr_book", "1", 5, "F");




flags = flags + 1;









if ( qglobals.cl_mmarr_book ) then





eq.delete_global("cl_mmarr_book");






else




eq.set_global("cl_mmarr_book", "1", 5, "F");




flags = flags + 1;







end
