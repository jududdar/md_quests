# Guard Donlan
## Dialog

**You say:** `hail`



>**Guard Donlan says:** Welcome, traveler. Have I informed you about the [travel tax]?

**You say:** `travel tax`



>**Guard Donlan says:** The travel tax is a fee of one gold for the privilege of using the highways of Karana. Oh! You know what? You must've used the roads to get here! I guess you owe me 1 gold!
end

## Turn-Ins



**This NPC *should* return incorrect items given.**

## Signals

if(e.signal == 1) then


>**Guard Donlan says:** Time to push our weight around. Ahhh. There is nothing better than being a Qeynos Guard.


eq.start(19)
end

## Arrive at Waypoint Script

if(e.wp == 1) then


>**Guard Donlan says:** You know the routine. You give me sixty percent of the McMannus profit and you can continue living. Unless, of course, the McMannus family can take on the entire Qeynos Guard..?


**Signaled to:**  [Sera McMannus](/npc/12095)

elseif(e.wp == 2) then


eq.stop();


eq.move_to(-2042,-2912,44,164,true);
end