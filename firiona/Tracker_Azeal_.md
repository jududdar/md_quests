# Tracker Azeal 



## Turn-Ins





if(e.self:GetX() == -1548 and e.self:GetY() == -2559) then


if **You turn in:** [A Coin](/item/12691)



>*Tracker Azeal  begins to pull his face off.. it is a disguise!! 'Aha!! You have made it!! I cannot see well in this disguise, but I thought I smelled you. I have [news of the Charasis tome].'*



e.other:Ding();



**Spawn NPC:**  [Hero Goxnok](/npc/84319) at this location.



**Spawn NPC:**  [a drachnid spy](/npc/84311) at (**y:** 617, **x:** -1822)



**Tracker Azeal  despawns.**


**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

if(e.wp == 7) then


e.self:DoAnim(36);
end






