# EinoInvisDay
local BANSHEE_TYPE = 204015; 
local NIGHTSTALKER_TYPE = 204019; 
local HOBGOBLIN_TYPE = 204011; 
local TREMULOUS_BAT_TYPE = 204030; 
local TERROR_BAT_TYPE = 204042; 
local TORMENT_BAT_TYPE = 204031; 

local MOB_TYPES = { [BANSHEE_TYPE] = 1, [NIGHTSTALKER_TYPE] = 1, [HOBGOBLIN_TYPE] = 1, [TREMULOUS_BAT_TYPE] = 1, [TERROR_BAT_TYPE] = 1, [TORMENT_BAT_TYPE] = 1 };



## On NPC Spawn

eq.debug("EinoInvisDay spawn", 2);

**Set a timer** named *timecheck* for 10 seconds















local npcList = eq.get_entity_list():GetNPCList();



if ( npcList ) then


for npc in npcList.entries do



if ( npc.valid ) then




if ( MOB_TYPES[npc:GetNPCTypeID()] ) then





if ( npc:GetX() > 480 and not npc:IsEngaged() ) then






npc:Depop();










end



## Timer(s)

if ( e.timer == "timecheck" ) then


local zoneTime = eq.get_zone_time()["zone_hour"];


if ( zoneTime > 19 or zoneTime < 7 ) then



eq.debug("EinoInvisDay despawn", 2);



**EinoInvisDay despawns.**

end
