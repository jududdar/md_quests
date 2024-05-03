# Deyid the Twisted
local SEILAEN_TYPE = 204047; 
local FOREBODING_TYPE = 204484; 
local BLIGHTED_TYPE = 204459; 
local CORRUPT_TYPE = 204460; 

local FOREBODING_LOCS = {

{ x = 1105, y = 926, z = 280.376, h = 234, x2 = 1087, y2 = 965, z2 = 279.6 },

{ x = 1032, y = 900, z = 280.376, h = 251, x2 = 1025, y2 = 939, z2 = 281, t = BLIGHTED_TYPE },

{ x = 910, y = 912, z = 280.376, h = 22, x2 = 931, y2 = 945, z2 = 283 },

{ x = 833, y = 978, z = 280.376, h = 43, x2 = 874, y2 = 1006, z2 = 275 },

{ x = 785, y = 1073, z = 280.376, h = 62, x2 = 828, y2 = 1077, z2 = 283.5, t = CORRUPT_TYPE },

{ x = 773, y = 1184, z = 280.376, h = 81 },

{ x = 853, y = 1289, z = 278.68, h = 101, x2 = 886, y2 = 1250, z2 = 277 },

{ x = 1003, y = 1270, z = 280.376, h = 128, x2 = 1000, y2 = 1236, z2 = 283, t = BLIGHTED_TYPE },

{ x = 1084, y = 1205, z = 280.376, h = 149, x2 = 1072, y2 = 1181, z2 = 280.9 },

{ x = 1181, y = 1110, z = 278.924, h = 184, x2 = 1154, y2 = 1106, z2 = 280.376 },

{ x = 1194, y = 999, z = 279.407, h = 209, x2 = 1155, y2 = 1028, z2 = 280, t = CORRUPT_TYPE },
};

local forebodingIDs;



## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds

**Set a timer** named *checkbounds* for 5 seconds

eq.set_next_hp_event(85);

forebodingIDs = {};
function event_hp(e)

if ( e.hp_event == 85 ) then


eq.set_next_hp_event(60);


local mob;





for _, coords in ipairs(FOREBODING_LOCS) do



mob = eq.spawn2(FOREBODING_TYPE, 0, 0, coords.x, coords.y, coords.z, coords.h or 0);



table.insert(forebodingIDs, mob:GetID());



eq.get_entity_list():MessageClose(e.self, true, 200, 0, "A low groaning sound wells up out of the surrounding woods as the rustling of leaves indicate something sinister is manifesting");




elseif ( e.hp_event == 60 ) then


eq.set_next_hp_event(45);


local mob;


local coords;


for i, id in ipairs(forebodingIDs) do



coords = FOREBODING_LOCS[i];



mob = eq.get_entity_list():GetMob(id);



if ( coords.x2 ) then




mob:CastToNPC():MoveTo(coords.x2, coords.y2, coords.z2, -1, true);





eq.get_entity_list():MessageClose(e.self, true, 200, 0, "Deyid the Twisted waves his branches about in agitation and the surrounding trees close in.");



elseif ( e.hp_event == 45 ) then


local mob, mob2;



for i, id in ipairs(forebodingIDs) do



mob = eq.get_entity_list():GetMob(id);



if ( FOREBODING_LOCS[i].t ) then




mob2 = eq.spawn2(FOREBODING_LOCS[i].t, 0, 0, mob:GetX(), mob:GetY(), mob:GetZ(), mob:GetHeading());




mob2:CastToNPC():MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), -1, false);




mob:Depop();





eq.get_entity_list():MessageClose(e.self, true, 200, 0, "Several of the foreboding trees tear their roots from the ground and move in to aid Deyid.");
end



## On NPC Death

eq.signal(SEILAEN_TYPE, 1);

eq.signal(FOREBODING_TYPE, 1);


## Timer(s)

if ( e.timer == "checkbounds" ) then


if ( e.self:GetZ() < 270 ) then



e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());



**Deyid the Twisted** clears hate list.



e.self:Heal();



**Deyid the Twisted casts:** [Balance of the Nameless](/spell/3230) on themselves.



eq.set_next_hp_event(85);



eq.depop_all(FOREBODING_TYPE);



eq.depop_all(BLIGHTED_TYPE);



eq.depop_all(CORRUPT_TYPE);



forebodingIDs = {};





elseif ( e.timer == "depop" ) then


eq.signal(SEILAEN_TYPE, 2);


eq.depop_all(FOREBODING_TYPE);


eq.depop_all(BLIGHTED_TYPE);


eq.depop_all(CORRUPT_TYPE);


**Deyid the Twisted despawns.**
end
