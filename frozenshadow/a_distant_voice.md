# a distant voice







## On NPC Spawn

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

eq.set_proximity(xloc - 45, xloc + 45, yloc - 45, yloc + 45, zloc - 3, zloc + 6);
function event_enter(e)

>**a distant voice says:** She took us during the battle. She could feel us dying during our struggle with the heretics. She brought us here, far from home. Do you see why you must go back now? Look at what she has done. They do not see, they think they are home. She feeds her captive souls with knowledge to power her tools of domination. Soon they will be bricks and steel, used for nothing but war.

**a distant voice despawns.**