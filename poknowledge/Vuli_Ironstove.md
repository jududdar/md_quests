# Vuli Ironstove



[Vuli Ironstove](/npc/202090) is a level 60 Erudite Shopkeeper that spawns in [Plane of Knowledge](/zone/202).



## Dialog

**You say:** `Hail`



>**Vuli Ironstove says:** Welcome. traveler! The Ironstoves pride ourselves upon our goods. for no other baker in the whole of the cosmos can hold a candle to our quality. Please. search my inventory and if you do not find that which you are searching for. then search my brethren's stock. I guarantee that among the five of us. you will find the exact ingredient you seek.
end



## On NPC Spawn

x = e.self:GetX();

y = e.self:GetY();

eq.set_proximity(x - 90, x + 90, y - 90, y + 90);
function event_enter(e)

**Signaled to:** 202273


## Turn-Ins



**This NPC *should* return incorrect items given.**





