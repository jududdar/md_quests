# Agent of The Tribunal
local SPAWNPOINT_IDS = { [345314] = 1, [345318] = 2, [345313] = 3, [345315] = 4, [345316] = 5, [345317] = 6 };
local CONTROLLER_IDS = { 201512, 201511, 201513, 201514, 201515, 201510 };

## Dialog

local trialNum = SPAWNPOINT_IDS[e.self:GetSpawnPointID()];



**You say:** `hail`



>**Agent of The Tribunal says:** Are you ready to [return]?


**You say:** `return`



if ( eq.get_entity_list():IsMobSpawnedByNpcTypeID(CONTROLLER_IDS[trialNum]) ) then



>**Agent of The Tribunal says:** The trial is yet underway.  You must wait.


else



e.other:CastToClient():MovePC(201, 473, 685, 10, 0);



if ( e.other:GetPet().valid and not e.other:GetPet():Charmed() ) then




e.other:GetPet():GMMove(473, 685, 10, 0);



end
