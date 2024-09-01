# Krazen Loosh

[Krazen Loosh](/npc/9143) is a level 10 Guard Warrior that spawns in [West Freeport](/zone/9).

Their primary faction is [The Freeport Militia](/faction/330).

## On NPC Spawn
e.self:SetRunning(true);




## Dialog
**You say:** `hail`

>**Krazen Loosh says:** The towering wall of stone is clearly unmovable at this point, being held in place by collection of magical energies.





## Arrive at Waypoint Script
if(e.wp == 8) then
>**Krazen Loosh says:** Hello, Alayle. We just got a message from Qeynos. I think you should come with me.
**Signaled to:**  [Guard Alayle](/npc/9141)
e.self:SetRunning(false);





## Signals
>**Krazen Loosh says:** As you try to open penetrate the stone wall it is clearly being held in place by a powerful force.
**Krazen Loosh attacks NPC:** 9141
**Signaled to:**  [Guard Lithnon](/npc/9106)


