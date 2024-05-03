# Executioner


## Dialog

**You say:** `hail`



>**Executioner says:** I have no time to talk, citizen. Please, step aside!
end



## Arrive at Waypoint Script

if(e.wp == 14) then


>**Executioner says:** Sir. You called for me?


**Signaled to:**  [Captain Tillin](/npc/1068)

elseif(e.wp == 40) then


>**Executioner says:** McNeal Jocub? You have been found guilty of crimes against the city of Qeynos.

elseif(e.wp == 41) then


**Signaled to:**  [McNeal Jocub](/npc/1099)
end



## Signals

>**Executioner says:** Aye sir!