# Helix Jeson



[Helix Jeson](/npc/208063) is a level 66 Human Warrior that spawns in [Plane of Valor](/zone/208).

local clientIDs = {};



## Dialog


**You say:** `hail`






if ( clientIDs[e.other:GetID()] ) then



>**Helix Jeson says:** You heard the Sergeant. Leave before we are forced to escort you out of the compound.


else



>**Helix Jeson says:** I have no time to talk Soandso. We are extremely busy at the moment.

end




## Signals

clientIDs[e.signal] = true;