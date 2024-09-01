# Executioner

[Executioner](/npc/1202) is a level 38 Barbarian Warrior that spawns in [South Qeynos](/zone/1).

Their primary faction is [Guards of Qeynos](/faction/262).

## Dialog
**You say:** `hail`

>**Executioner says:** I have no time to talk, citizen. Please, step aside!





## Arrive at Waypoint Script
if(e.wp == 14) then
>**Executioner says:** Sir. You called for me?
**Signaled to:**  [Captain Tillin](/npc/1068)
elseif(e.wp == 40) then
>**Executioner says:** McNeal Jocub? You have been found guilty of crimes against the city of Qeynos.
elseif(e.wp == 41) then
**Signaled to:**  [McNeal Jocub](/npc/1099)





## Signals
>**Executioner says:** Aye sir!
