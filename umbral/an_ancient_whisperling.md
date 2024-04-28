# an ancient whisperling
## On NPC Spawn

**Set a timer** named *proxsay* for 2 seconds
## Timer(s)

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

eq.set_proximity(xloc - 45, xloc + 45, yloc - 45, yloc + 45);

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



>**an ancient whisperling says:** Your x is ".. xdiff .." and your y is " .. ydiff .." from me!



**You say:** `worthy of vah kerrath`



>**an ancient whisperling says:** The squishy mortal has proven itself by releasing Elysian spirits. We greet the Elysian spirits to our realm and rejoice in their freedom. Go on fleshling, ask the bone man to tell you of Vex Thal.
end

