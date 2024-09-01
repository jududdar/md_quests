# Key Master

[Key Master](/npc/71056) is a level 55 Dwarf Shopkeeper that spawns in [Plane of Sky](/zone/71).

Their primary faction is [Inhabitants of Sky](/faction/424).

## Signals
local qglobals = eq.get_qglobals();


if(e.signal == 1) then 
if(**spawned NPC:**  [an azarack](/npc/71111) == false and **spawned NPC:**  [an azarack](/npc/71031) == false) then
















## Dialog
**You say:** `hail`

>**Key Master says:** Hello there, brave traveller. I sell keys that take you to other islands in this here Plane of Sky. My prices are the best around. Heh, heh.
**You say:** `what.* key`

>**Key Master says:** The keys? Heh, heh... Well, let's just say between you and me, them there faeries ain't much of the fightin' type. At least they ain't as strong as lotsa other stuff that's up on these here islands that we be standin' on now.





## Timer(s)
if(e.timer == "soul") then
**Stop timer** named *soul*



