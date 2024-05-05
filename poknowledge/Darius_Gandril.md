# Darius Gandril



[Darius Gandril](/npc/202138) is a level 60 Dark Elf Shopkeeper that spawns in [Plane of Knowledge](/zone/202).



## Dialog

**You say:** `Hail`



>**Darius Gandril says:** Good day to you. traveler. The trails of the outer planes and Norrath alike take their tolls upon any adventurer. The need for supplies is great to maintain strength. agility. awareness. and focus and thus. I provide that which may quench your common desires. Search my stock as you wish and purchase what catches your eye. My prices are most fair. I assure you.
end



## On NPC Spawn

x = e.self:GetX();

y = e.self:GetY();

eq.set_proximity(x - 90, x + 90, y - 90, y + 90);
function event_enter(e)

**Signaled to:** 202274


## Turn-Ins



**This NPC *should* return incorrect items given.**





