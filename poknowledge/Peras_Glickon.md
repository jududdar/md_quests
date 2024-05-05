# Peras Glickon



[Peras Glickon](/npc/202137) is a level 60 Wood Elf Shopkeeper that spawns in [Plane of Knowledge](/zone/202).



## Dialog

**You say:** `Hail`



>**Peras Glickon says:** Greetings. traveler! If you have come searching to restock on reagents. then I am most glad to see you. Please. browse my wares and purchase whatever you need from my stock.
end



## On NPC Spawn

x = e.self:GetX();

y = e.self:GetY();

eq.set_proximity(x - 90, x + 90, y - 90, y + 90);
function event_enter(e)

**Signaled to:** 202273


## Turn-Ins



**This NPC *should* return incorrect items given.**





