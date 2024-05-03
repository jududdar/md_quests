# Guard Dagur


## Dialog

**You say:** `hail`



>**Guard Dagur says:** Greetings and welcome to Thurgadin, " .. e.other:Race() .. ". Ye best watch yer step on the bridge there, it can be a bit slippery.


if(**spawned NPC:**  [Guard Baldvin](/npc/115132)) then



eq.get_entity_list():GetMobByNpcTypeID( [Guard Baldvin](/npc/115132)):Say("Aye, we wouldn't want ye fallin into the pit now would we."); 

end
