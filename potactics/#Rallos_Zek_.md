# Rallos Zek 
local CORPSE_TYPES = { [214007] = 1, [214008] = 1, [214009] = 1, [214010] = 1, [214011] = 1 };

function GetCorpse()

local npcList = eq.get_entity_list():GetNPCList();



for npc in npcList.entries do




if ( npc.valid ) then






if ( CORPSE_TYPES[npc:GetNPCTypeID()] ) then




return npc;






end

function DepopCorpses()

local npcList = eq.get_entity_list():GetNPCList();



for npc in npcList.entries do




if ( npc.valid ) then






if ( CORPSE_TYPES[npc:GetNPCTypeID()] ) then




npc:Depop(true);






end

function GetWraith()

local npcList = eq.get_entity_list():GetNPCList();



for npc in npcList.entries do




if ( npc.valid ) then






if ( npc:GetNPCTypeID() == 214305 ) then 




local spawnId = npc:GetSpawnPointID();




if ( spawnId == 361197 or spawnId == 361205 or 361205 == 361211 ) then 





return npc;









end



## On NPC Spawn

**Set a timer** named *corpses* for 60 seconds


## Timer(s)

if ( e.timer == "corpses" ) then




local roll = math.random(100);


local corpse, spawn;





if ( roll < 60 ) then



corpse = GetCorpse();



if ( corpse and corpse.valid ) then




eq.get_entity_list():MessageClose(corpse, true, 150, 0, "A corpse is renewed by the power of Rallos.  It has taken up arms in the eternal battle once more.");




spawn = eq.spawn2(eq.ChooseRandom(214015, 214017, 214021, 214090), 29, 0, corpse:GetX(), corpse:GetY(), corpse:GetZ(), 0); 




spawn:CastToNPC():SetWaypointPause();




eq.set_timer("depop", 300000, spawn);




corpse:Depop(true);








elseif ( roll < 85 ) then



corpse = GetCorpse();



if ( corpse and corpse.valid ) then




eq.get_entity_list():MessageClose(corpse, true, 150, 0, "A corpse is rent by the power of Zek.  It has been found lacking.");




spawn = eq.spawn2(214078, 29, 0, corpse:GetX(), corpse:GetY(), corpse:GetZ(), 0); 




spawn:CastToNPC():SetWaypointPause();




eq.set_timer("depop", 300000, spawn);




corpse:Depop(true);




else



corpse = GetWraith();



if ( corpse and corpse.valid ) then




eq.get_entity_list():MessageClose(corpse, true, 150, 0, "A War Wraith raises its hands and begins to howl.  The bodies of the fallen are torn asunder as the judgement of Zek consumes them.");





DepopCorpses();






eq.set_timer(e.timer, math.random(15, 180) * 1000);
end
