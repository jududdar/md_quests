# Aid Eino
local BANSHEE_TYPE = 204015; 
local NIGHTSTALKER_TYPE = 204019; 
local HOBGOBLIN_TYPE = 204011; 
local TREMULOUS_BAT_TYPE = 204030; 
local TERROR_BAT_TYPE = 204042; 
local TORMENT_BAT_TYPE = 204031; 
local DREAMKEEPER_TYPE = 204480; 

local INVIS_MAN_SPAWNPOINTID = 345856;

local escortDone = false;

## On NPC Spawn

>*Aid Eino steps from the shadows 'I am glad you were able to come help me, this is quite a dangerous realm!  We must tread carefully if we are to find the item Kerasha desires from this vile place.  Sometimes I worry her research with the magic of the land puts her in much danger.  Let us be off and find that which she desires.'*

**Set a timer** named *setrespawn* for 1 seconds

escortDone = false;
## Timer(s)

if ( e.timer == "setrespawn" ) then


**Stop timer** named *setrespawn*


eq.get_entity_list():GetSpawnByID(INVIS_MAN_SPAWNPOINTID):SetTimer(2160000);

elseif ( e.timer == "depop" ) then


**Aid Eino despawns.**
end

## Arrive at Waypoint Script



if ( e.wp == 2 ) then


>**Aid Eino says:** Vile Beasts!  Our presence has been detected!  Let not their dreams of evil sway you!


eq.spawn2(BANSHEE_TYPE, 0, 0, 992, -1083, 213, 106);


eq.spawn2(BANSHEE_TYPE, 0, 0, 1053, -1147, 216, 216);


eq.spawn2(BANSHEE_TYPE, 0, 0, 971, -1124, 212, 60);


eq.spawn2(BANSHEE_TYPE, 0, 0, 1071, -1101, 215, 179);




elseif ( e.wp == 3 ) then


>**Aid Eino says:** Even in my home I always hated werewolves, I fear you not vile fiends!


eq.spawn2(NIGHTSTALKER_TYPE, 0, 0, 586, -1625, 209.664, 172);


eq.spawn2(NIGHTSTALKER_TYPE, 0, 0, 532, -1583, 208, 123);



elseif ( e.wp == 4 ) then


>**Aid Eino says:** Have you ever had a dream where you were being chased and could not run?  This place is the source of such nightmares.  Break those blocks and defend yourself!


eq.spawn2(HOBGOBLIN_TYPE, 0, 0, 524, -611, 213, 98);


eq.spawn2(HOBGOBLIN_TYPE, 0, 0, 505, -674, 213, 53);


eq.spawn2(HOBGOBLIN_TYPE, 0, 0, 552, -722, 211, 8);


eq.spawn2(HOBGOBLIN_TYPE, 0, 0, 624, -694, 212, 214);


eq.spawn2(HOBGOBLIN_TYPE, 0, 0, 589, -631, 217, 157);



elseif ( e.wp == 6 ) then


>**Aid Eino says:** Something knows we hunt it!  Cast your trepidations aside and defeat this evil!  Fear us Keeper, we have come for you!


eq.spawn2(BANSHEE_TYPE, 0, 0, 492, 659, 212, 56);


eq.spawn2(BANSHEE_TYPE, 0, 0, 576, 597, 212, 7);


eq.spawn2(BANSHEE_TYPE, 0, 0, 677, 652, 215, 202);


eq.spawn2(BANSHEE_TYPE, 0, 0, 604, 767, 211, 134);


eq.spawn2(eq.ChooseRandom(TREMULOUS_BAT_TYPE, TREMULOUS_BAT_TYPE, TERROR_BAT_TYPE, TORMENT_BAT_TYPE), 0, 0, 527, 610, 213, 31);


eq.spawn2(eq.ChooseRandom(TREMULOUS_BAT_TYPE, TREMULOUS_BAT_TYPE, TERROR_BAT_TYPE, TORMENT_BAT_TYPE), 0, 0, 627, 602, 214, 236);


eq.spawn2(eq.ChooseRandom(TREMULOUS_BAT_TYPE, TREMULOUS_BAT_TYPE, TERROR_BAT_TYPE, TORMENT_BAT_TYPE), 0, 0, 650, 732, 210, 161);


eq.spawn2(eq.ChooseRandom(TREMULOUS_BAT_TYPE, TREMULOUS_BAT_TYPE, TERROR_BAT_TYPE, TORMENT_BAT_TYPE), 0, 0, 538, 719, 209, 91);




elseif ( e.wp == 7 ) then


e.self:SetAppearance(1); 


elseif ( e.wp == 8 ) then


>**Aid Eino says:** The fiend shows itself!  Spew your vile dreams no longer!  Dispatch it!


local mob = eq.unique_spawn(DREAMKEEPER_TYPE, 0, 0, 578, 717, 205, 129);



elseif ( e.wp == 10 ) then


>**Aid Eino says:** Hand me the strand from the beast.  Quellious knows what Kerasha wants with such a thing.


**Set a timer** named *depop* for 1800 seconds


escortDone = true;
end

## Depart from Waypoint Script

if ( e.wp == 2 ) then


>**Aid Eino says:** Now that our presence here is discovered we cannot delay. Rest when you can.

elseif ( e.wp == 3 or e.wp == 4 ) then


>**Aid Eino says:** Now that you are rested, follow my steps, may Quellious guard us!

elseif ( e.wp == 6 ) then


>**Aid Eino says:** Excellent rest up for a few moments, rally your strength as I meditate on a teaching of Quellious.

elseif ( e.wp == 8 ) then


>*Aid Eino holds his bleeding side. 'That beast was quite vicious. Quickly! Let us make our way to the portal. I must seek the healers of tranquility to stanch the bleeding of this wound.  Give me a moment to gather my strength.'*

elseif ( e.wp == 9 ) then


>*Aid Eino gathers his strength and limps forward. 'Follow my steps to the portal!'*
end

## Turn-Ins





if ( escortDone and  **You turn in:** [Strand of Nightmare](/item/16261) ) then 


>**Aid Eino says:** Excellent!  You and your companions have served me well, take my mark as a symbol of trust.  The Council may smile more favorably upon you now.  May Quellious watch over you!


 **You receive:**  [Tiny Gold Fist](/item/16260) 


**Aid Eino despawns.**


**This NPC *should* return incorrect items given.**
;