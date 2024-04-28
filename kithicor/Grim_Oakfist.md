# Grim Oakfist
local EENOT_SPAWN_LOCS = {

{ 898, -137, 108 },

{ 500, -645, 27 },

{ 1972, -800, [Silent Fist Clan](/faction/309) },

{ 2024, -118, 297 },

{ 2977, -479, 389 },

{ 3464, -833, 511 },

{ 4184, -745, 548 }
}

local REGGIT_SPAWN_LOCS = {

{ 4206, -440, 502 },

{ 4086, -589, 490 },

{ 3637, -545, 442 },

{ 2684, -739, 417 },

{ 2269, -613, 269 },

{ 2002, -732, 287 },

{ 979, -592, 215 },

{ 783, -547, 142 },
}

local KOBB_SPAWN_LOCS = {

{ 876, -58, 98 },

{ 2927, 886, 346 },

{ 1861, 315, 216 },

{ 666, 944, 56 },

{ 1047, 1366, 118 },

{ 2117, 1265, 255 },

{ 2514, 1704, 307 },

{ 1131, 1632, 211 },

{ 542, 1713, 57 },

{ 1255, 505, 142 }
}

## Dialog

if **Faction** <  Indifferent then


**Grim Oakfist says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

elseif **Faction** <  Amiable then


>**Grim Oakfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.

elseif **Faction** >= Amiable then


**You say:** `hail`




>**Grim Oakfist says:** It is good to finally meet one who respects the disciplines of the Ashen Order.  All I have met are rangers.  They have interfered with my [mission in the woods].


**You say:** `mission in the wood`




>**Grim Oakfist says:** I have come here to avenge my family.  One season past, they were attacked by a trio of deadly tigers.  I came here to hunt the beasts down, but then I found the local rangers and residents here protect the tigers.  They seem to be legends in these parts.  The tigers even have name's!!  They call them Eenot, Reggit and Kobb.  I wish I had help from a [fellow monk].


**You say:** `fellow monk`




>**Grim Oakfist says:** Good!! The rangers are watching me so you must go alone.  I can only wait until the morning, then I must go.  If you find all three tigers, return their pelts to me and I shall reward you with something discovered for monks only.



TigerSpawns(e);


**You say:** `treant fist`




>**Grim Oakfist says:** The treant fists were created by great craftsmen.  They are for the fists of a monk and offer greater dexterity and increase the durability of one's soul.  My last pair were given to Master Puab of the Ashen House training grounds.



**Grim Oakfist despawns.**

end

## Turn-Ins



local text = "I asked you to hunt down all three of the tigers.";



if **Faction** >= Amiable and  **You turn in:** [Unusual Tiger Pelt](/item/12341), [Peculiar Tiger Pelt](/item/12342), [Strange Tiger Pelt](/item/12343)


>**Grim Oakfist says:** Good work.  I hope you had no run ins with the local rangers.  Here is my reward.  An object from the past which I found in my journeys.  Wish that I could reward you also with [treant fists].


* __Faction:__ [Ashen Order](/faction/361) (10)


* __Faction:__ [Knights of Truth](/faction/281) (1)


* __Faction:__ [Silent Fist Clan](/faction/309) (1)


 **You receive:**  [Collar of Neshika](/item/12367) 


**Grim Oakfist despawns.**

**This NPC *should* return incorrect items given.**

function TigerSpawns(e)

local eenot_loc = EENOT_SPAWN_LOCS[math.random(1, #EENOT_SPAWN_LOCS)];

local reggit_loc = REGGIT_SPAWN_LOCS[math.random(1, #REGGIT_SPAWN_LOCS)];

local kobb_loc = KOBB_SPAWN_LOCS[math.random(1, #KOBB_SPAWN_LOCS)];



**Spawn NPC:**  [Eenot](/npc/20276) at (**y:** , **x:** )

**Spawn NPC:**  [Reggit](/npc/20277) at (**y:** , **x:** )

**Spawn NPC:**  [Kobb](/npc/20000) at (**y:** , **x:** )
end