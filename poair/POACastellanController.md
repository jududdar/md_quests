# POACastellanController
local CASTELLAN_TYPE = 215000; 
local ALRANDERISAN_TYPE = 215383; 
local BELECOHEN_TYPE = 215384; 
local FERABALEN_TYPE = 215385; 
local CHAMBERLAIN_TYPE = 215411; 
local APPRENTICE_TYPE = 215410; 
local ARMOR_GUY_TYPE = 215418; 

local CASTELLAN_SPAWNIDS = { 365333, 365444, 365629, 365679, 365833, 366093, 366315, 366369, 366414, 366612, 







366707, 366798, 367079, 367099, 367284 };
local LOCS = {

[ALRANDERISAN_TYPE] = { 403, 463, -88.5 },

[BELECOHEN_TYPE] = { 518, 456, -88.5 },

[FERABALEN_TYPE] = { 461, 498, -85.875 },
};

local signals = {};
local kills = 0;
local spawns = { ALRANDERISAN_TYPE, BELECOHEN_TYPE, FERABALEN_TYPE };

function RepopIsland()

local elist = eq.get_entity_list();


for _, id in ipairs(CASTELLAN_SPAWNIDS) do


elist:GetSpawnByID(id):Repop();



kills = 0;



for i = 2, 4 do


signals[i] = nil;


spawns[1] = eq.ChooseRandom(ALRANDERISAN_TYPE, BELECOHEN_TYPE, FERABALEN_TYPE);

spawns[2] = nil;

spawns[3] = nil;

while ( not spawns[2] ) do


spawns[2] = eq.ChooseRandom(ALRANDERISAN_TYPE, BELECOHEN_TYPE, FERABALEN_TYPE);


if ( spawns[2] == spawns[1] ) then



spawns[2] = nil;


while ( not spawns[3] ) do


spawns[3] = eq.ChooseRandom(ALRANDERISAN_TYPE, BELECOHEN_TYPE, FERABALEN_TYPE);


if ( spawns[3] == spawns[1] or spawns[3] == spawns[2] ) then



spawns[3] = nil;

end



## On NPC Spawn

**Set a timer** named *castellan_repop* for 1080 seconds


## Timer(s)


if ( e.timer == "castellan_repop" ) then


RepopIsland();
end



## Signals


if ( e.signal == 1 ) then




if ( eq.get_entity_list():IsMobSpawnedByNpcTypeID(CASTELLAN_TYPE) ) then



**Set a timer** named *castellan_repop* for 1080 seconds


else



**Set a timer** named *castellan_repop* for 10800 seconds






kills = kills + 1;



local t, mob;


if ( kills == 5 ) then



t = spawns[1];


elseif ( kills == 10 ) then



t = spawns[2];


elseif ( kills == 15 ) then



t = spawns[3];




if ( t ) then



loc = LOCS[t];



mob = eq.unique_spawn(t, 0, 0, LOCS[t][1], LOCS[t][2], LOCS[t][3], 0);



if ( mob and mob.valid ) then




eq.debug(mob:GetCleanName().." spawned");







else


signals[e.signal] = 1;





if ( signals[2] and signals[3] and signals[4] ) then






local elist = eq.get_entity_list();



local mob;







if ( not elist:IsMobSpawnedByNpcTypeID(CHAMBERLAIN_TYPE) and not elist:IsMobSpawnedByNpcTypeID(APPRENTICE_TYPE) ) then








if ( elist:IsMobSpawnedByNpcTypeID(ARMOR_GUY_TYPE) ) then





mob = eq.spawn2(CHAMBERLAIN_TYPE, 0, 0, 457, 412, -88.622, 0);




else





mob = eq.spawn2(APPRENTICE_TYPE, 0, 0, 457, 412, -88.622, 0);







if ( mob and mob.valid ) then





eq.debug(mob:GetCleanName().." spawned");







end
