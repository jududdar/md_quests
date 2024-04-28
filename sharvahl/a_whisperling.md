# a whisperling
## On NPC Spawn

**Set a timer** named *proxsay* for 2 seconds
## Timer(s)

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

eq.set_proximity(xloc - 35, xloc + 35, yloc - 35, yloc + 35);

eq.enable_proximity_say();

**Stop timer** named *proxsay*
function event_proximity_say(e)

local xloc = e.other:GetX();

local yloc = e.other:GetY();

local nxloc = e.self:GetX();

local nyloc = e.self:GetY();

local xdiff = xloc - nxloc;

local ydiff = yloc - nyloc;

**You say:** `hail`



>**a whisperling says:** Your x is ".. xdiff .." and your y is " .. ydiff .." from me!



**You say:** `lumanes`



>*a whisperling speaks softly, 'Lumanes Soandso, Our cousin, a spirit of frost, is trapped. We may not intervene. Only one of flesh may aid us. Are you one [able to help]? '*

**You say:** `able to help`



>**a whisperling says:** speaks softly, 'Then we thank you. We will lure it here. But beware, it uses our cousins strength to protect itself.'


**Spawn NPC:**  [a frost covered hopling](/npc/155005) at this location.


**a whisperling despawns.**
end

