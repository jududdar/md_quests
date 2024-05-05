# IanitorGovernor







local SPAWNIDS = { 334700, 334701, 334732 };
local INVIS_IANITOR = 163086;

function CheckSpawns()


local npcList = eq.get_entity_list():GetNPCList();

local numSpawns = 0;



if ( npcList ) then




for npc in npcList.entries do




if ( npc.valid and npc:GetNPCTypeID() == INVIS_IANITOR ) then




numSpawns = numSpawns + 1;






if ( numSpawns == 3 ) then



eq.debug("#Prast_Ianitor did not spawn; repopping");



DepopSpawns();



**Set a timer** named *repop* for 3 seconds

end

function DepopSpawns()

local npcList = eq.get_entity_list():GetNPCList();


if ( npcList ) then




for npc in npcList.entries do








if ( npc.valid and npc:GetNPCTypeID() == INVIS_IANITOR ) then




npc:Depop(true);



end



## Signals

if ( e.signal == 1 ) then


CheckSpawns();
end



## Timer(s)

if ( e.timer == "repop" ) then


**Stop timer** named *repop*


for _, id in ipairs(SPAWNIDS) do



eq.spawn_from_spawn2(id);

end
