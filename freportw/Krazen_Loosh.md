# Krazen Loosh


## On NPC Spawn

e.self:SetRunning(true);


## Dialog

**You say:** `hail`



>**Krazen Loosh says:** The towering wall of stone is clearly unmovable at this point, being held in place by collection of magical energies.
end



## Arrive at Waypoint Script

if(e.wp == 8) then


>**Krazen Loosh says:** Hello, Alayle. We just got a message from Qeynos. I think you should come with me.


**Signaled to:**  [Guard Alayle](/npc/9141)


e.self:SetRunning(false);
end



## Signals


>**Krazen Loosh says:** As you try to open penetrate the stone wall it is clearly being held in place by a powerful force.


**Krazen Loosh attacks NPC:**  [Guard Alayle](/npc/9141)


**Signaled to:**  [Guard Lithnon](/npc/9106)


