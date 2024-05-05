# Jiva



[Jiva](/npc/212014) is a level 75 Efreeti Warrior that spawns in [Tower of Solusek Ro](/zone/212).

local TYPES = { 212404, 212399, 212403, 212406, 212405, 212400, 212401, 212402 };
local LOCS = {

{ -2255, -338, -1089.787 },

{ -2304, -312, -1097 },

{ -2328, -263, -1089.62 },

{ -2302, -214, -1089.574 },

{ -2255, -192, -1089.62 },

{ -2206, -216, -1097 },

{ -2183, -264, -1089.703 },

{ -2204, -314, -1090.085 },
};
local SAYS = {

"Makin, come to my aid!",

"Adeel, I require your assistance!",

"Jiri, lend me your help!",

"Seif, to my side!",

"Nabil, come to my aid!",

"Aydin, your knowledge of the arcane is needed!",

"Cemal, enchanted ones, I need your help!",

"Fahim, your control over the elements is needed!",
};

local add = 0;




## On NPC Death

**Spawn NPC:**  [a flaming cauldron](/npc/212412) at (**y:** 105, **x:** -2126)


**Spawn NPC:**  [a warder of Jiva](/npc/212417) at (**y:** -790, **x:** -2211)


**Spawn NPC:**  [a warder of Jiva](/npc/212417) at (**y:** -790, **x:** -2255)

**Spawn NPC:**  [a warder of Jiva](/npc/212417) at (**y:** -790, **x:** -2301)


## Combat

if  Jiva enters combat  then


**Set a timer** named *adds* for 45 seconds


add = 0;

else


**Stop timer** named *adds*
end



## Timer(s)

if ( e.timer == "adds" ) then


add = add + 1;


if ( add > #TYPES ) then



add = 1;



eq.spawn2(TYPES[add], 0, 0, LOCS[add][1], LOCS[add][2], LOCS[add][3], 0);


e.self:Say(SAYS[add]);
end
