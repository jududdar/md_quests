# Warder Keeper Jyk



[Warder Keeper Jyk](/npc/155169) is a level 5 Vah Shir Warrior that spawns in [The City of Shar Vahl](/zone/155).



## Arrive at Waypoint Script

if(e.wp == 1) then


e.self:SetAppearance(3);

if(e.wp == 21) then


>*Warder Keeper Jyk grabs a large chunk of raw owlbear meat from the storeroom.*

if(e.wp == 35) then


>**Warder Keeper Jyk says:** hail Palav. It's feeding time my friend. Now now Rajyk, It's ladies first. I will return with your food shortly.


**Signaled to:**  [Palav](/npc/155289)


**Signaled to:**  [Rajyk](/npc/155288)

if(e.wp == 47) then


>*Warder Keeper Jyk grabs a large chunk of raw owlbear meat from the storeroom.*

if(e.wp == 59) then


>**Warder Keeper Jyk says:** hail Rajyk. You didn't think I forgot to feed you did you? Eat well my friends, I will be back again.


**Signaled to:**  [Palav](/npc/155289)


**Signaled to:**  [Rajyk](/npc/155288)

if(e.wp == 67) then


>**Warder Keeper Jyk says:** My my, what a selection. I think I'll go with some ale today.

if(e.wp == 78) then


e.self:SetAppearance(1);
end



## Dialog

**You say:** `Hail`



>**Warder Keeper Jyk says:** Well met. friend.  May I be of assistance?
end



## Turn-Ins



**This NPC *should* return incorrect items given.**





