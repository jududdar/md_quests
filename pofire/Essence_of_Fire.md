# Essence of Fire



[Essence of Fire](/npc/217454) is a level 1 Fire Elemental Warrior that spawns in [Plane of Fire](/zone/217).

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

**Set a timer** named *depop* for 1200 seconds

flags = 0;


## Combat

if  Essence of Fire enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## Timer(s)

if ( e.timer == "depop" ) then


**Essence of Fire despawns.**
end



## Dialog


**You say:** `hail`






if ( not **You possess item:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/29147" data-url="29147" class="tooltip-link link">Globe of Dancing Flame</a> x 1



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/29147" data-url="29147" class="tooltip-link link">Globe of Dancing Flame</a>



flags = flags + 1;






if ( flags >= FLAG_LIMIT ) then



**Essence of Fire despawns.**

end
