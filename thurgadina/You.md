# You
local count = 0;

## On NPC Spawn

**Set a timer** named *proxsay* for 2 seconds
## Timer(s)

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

eq.set_proximity(xloc - 25, xloc + 25, yloc - 25, yloc + 25);

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



>**You says:** Your x is ".. xdiff .." and your y is " .. ydiff .." from me!



**You say:** `oh brell, thank you for protecting me and seeing me through my trials. forgive me for the things I think and say and do that displease you. Please reveal to me your will and bless me with the patience and obedience to do that which you desire. amen`



count = count + 1;



if (count == 3) then


>*You have been inspired. The sacred pattern of the Coldain rune materializes on the ground before you.*


**Spawns on ground:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/1855" data-url="1855" class="tooltip-link link">Etched Rune pattern</a> at (**y:** -320, **x:** 793)


count = 0;
end

