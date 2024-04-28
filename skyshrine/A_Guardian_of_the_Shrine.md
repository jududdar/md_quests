# A Guardian of the Shrine
local SLEEPER_TYPE = 128094; 
local SHOUT_TYPES = { 114618, 114508, 114435, 114564, 114434, 114501, 114014 };

## Signals

if ( e.signal == 1 ) then


eq.debug("Sleeper timer started");





local npc;


for i, id in ipairs(SHOUT_TYPES) do



npc = eq.get_entity_list():GetNPCByNPCTypeID(id);



if ( npc and npc.valid ) then








if ( i == 1 ) then 





eq.get_entity_list():MessageClose(npc, true, 1500, 0, npc:GetCleanName().." shouts, 'BEWARE!  The Sleeper has been awakened!  Flee the shrine immediately, it intends death to all here!'");




else





eq.get_entity_list():MessageClose(npc, true, 600, 0, npc:GetCleanName().." shouts, 'BEWARE!  BEWARE!  The Sleeper has been awakened!  He means death for all who remain here!  Time is short, flee the Skyshrine now if you value your life!'");









**Set a timer** named *sleeper* for 600 seconds
end

## Timer(s)

eq.stop_timer(e.timer);

if ( e.timer == "sleeper" ) then


**Set a timer** named *repop* for 86400 seconds





eq.spawn2(SLEEPER_TYPE, 0, 0, -328, 447, 46, 0, "Kerafyrm");





local npcList = eq.get_entity_list():GetNPCList();


for npc in npcList.entries do






if ( npc.valid and npc:GetPrimaryFaction() == 430 ) then 




npc:SetNPCAggro(true);








local spawnList = eq.get_entity_list():GetSpawnList();


for spawn in spawnList.entries do



spawn:Disable(false);





elseif ( e.timer == "repop" ) then


local spawnList = eq.get_entity_list():GetSpawnList();


for spawn in spawnList.entries do



spawn:Enable();



eq.debug("zone spawns enabled");
end
