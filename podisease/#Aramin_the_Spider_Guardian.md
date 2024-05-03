# Aramin the Spider Guardian
local MALEVELER_TYPE = 205157; 
local SERIOUN_TYPE = 205158; 
local SPAWN_LOCS = {

1763, 259,


1789, 226,

1842, 199,

1750, 214,

1721, 247,


1746, 187,

1783, 177,

1889, 270,
};



## On NPC Death


local x, y, t;

local z = 373;

local r1 = math.random(1, 2);

local r2 = math.random(7, 8);

if ( r1 == 2 ) then


r2 = 8;






for i = r1, r2 do



if ( i < 5 ) then



t = SERIOUN_TYPE;





else



t = MALEVELER_TYPE;






x = SPAWN_LOCS[i*2-1];


y = SPAWN_LOCS[i*2];





eq.spawn2(t, 0, 0, x, y, z, 0);
end
