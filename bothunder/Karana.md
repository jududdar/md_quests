# Karana
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

**Set a timer** named *depop* for 3300 seconds

flags = 0;
## Timer(s)

if ( e.timer == "depop" ) then


**Karana despawns.**
end

## Dialog


local qglobals = eq.get_qglobals(e.other);



if ( ClientCanFlag(e.other) ) then




**You say:** `hail`




>**Karana says:** Karana looks down at Soandso's face.  He seems so insignificant next to the massive stature of the Rainkeeper.  'Don't worry mortal, Askr is unharmed, I have set him on a journey that will take him to all corners of this reality.  He will either find the balance of the Fallen or he will die trying.  And what of you champions?  Do you wish to follow the path of the Fallen?  A more dangerous path has never existed.  Defy the will of the Pantheon at your peril.






**You say:** `follow the path of the Fallen`







local karana = tonumber(qglobals.karana or 0);







if ( karana == 3 ) then




**Message:** <span class="text-warning">*Karana begins to laugh quietly.  You seem to notice a great storm cloud brewing once more above him.  A sudden arching bolt hits you, but you are unharmed.  Instead a tome written in the language of the gods appears in your hands.  'Then let what I know be yours to know as well.  Your path leads you onward Soandso.  The path to power or ruin, the choice is up to you.  Speak the words and I will send you on your way.'*</span>




eq.set_global("karana", "4", 5, "F");




**Message:** <span class="text-warning">*You have received a character flag!*</span>




flags = flags + 1;









if ( qglobals.cl_karana ) then





eq.delete_global("cl_karana");











elseif ( karana < 3 and not qglobals.zebuxoruk ) then




**Message:** <span class="text-warning">*Karana begins to laugh quietly.  You seem to notice a great storm cloud brewing once more above him.  'Your path leads you onward mortals.  The path to power or ruin, the choice is up to you.  Speak the words and I will send you on your way.'*</span>




eq.set_global("cl_karana", "1", 5, "F");




**Message:** <span class="text-warning">*You have received a new checklist flag!*</span>




flags = flags + 1;











**You say:** `send me`




>*Karana nods and begins to utter the same unfamiliar words that sent Askr into the void.  The storm above him rises up and begins to spark sending chills up your spine.  The Rainkeeper's voice rises to an incredible wail as the storm rages through the room.  The cold rain pelting your face is the last thing you remember as a great bolt of pure storm energy envelopes you.*







**Karana casts:** [Gate](/spell/36) on target.

end
