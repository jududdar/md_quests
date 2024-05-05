# Tagrin Maldric



[Tagrin Maldric](/npc/214054) is a level 70 Troll Warrior that spawns in [Drunder, the Fortress of Zek](/zone/214).

local BLADE_TYPE1 = 214310; 
local BLADE_TYPE2 = 214326; 
local SPAWN_LOCS = {

{ 1260, 2136, -302.65 },

{ 1449, 1734, -305 },

{ 1246, 1775, -307 },

{ 1693, 1955, -305 },
};

local spawnCount = 0;

function CountBlades()

local npcList = eq.get_entity_list():GetNPCList();

local count = 0;



for npc in npcList.entries do




if ( npc.valid and (npc:GetNPCTypeID() == BLADE_TYPE1 or npc:GetNPCTypeID() == BLADE_TYPE2) ) then



count = count + 1;




return count;
function SpawnBlades(n, tagrin)

local loc, mob, tar, typ;

for i = 1, n do


loc = SPAWN_LOCS[math.random(1, 4)];





if ( spawnCount > 10 ) then 



typ = BLADE_TYPE2;


else



typ = BLADE_TYPE1;






mob = eq.spawn2(typ, 0, 0, loc[1], loc[2], loc[3], 0);


mob:SetRunning(true);


if ( tagrin:IsEngaged() ) then



tar = tagrin:GetHateRandomClient();



if ( tar and tar.valid ) then



mob:AddToHateList(tar, 20);






spawnCount = spawnCount + 1;
end

function AggroBlades(tagrin)

local npcList = eq.get_entity_list():GetNPCList();

local tar;



for npc in npcList.entries do




if ( npc.valid and (npc:GetNPCTypeID() == BLADE_TYPE1 or npc:GetNPCTypeID() == BLADE_TYPE2) ) then







if ( tagrin:IsEngaged() ) then




tar = tagrin:GetHateRandom();





if ( tar and tar.valid ) then




npc:AddToHateList(tar, 20);







end



## On NPC Spawn

spawnCount = 0;


## Combat

if  Tagrin Maldric enters combat  then


**Set a timer** named *tick* for 6 seconds


AggroBlades(e.self);

else


**Stop timer** named *tick*
end



## Timer(s)


if ( e.timer == "tick" ) then




if ( e.self:GetY() < 1685 ) then



e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());






**Tagrin Maldric** clears hate list.



**Tagrin Maldric casts:** [Balance of the Nameless](/spell/3230) on themselves.






local blades = CountBlades();





if ( blades < 3 ) then



SpawnBlades(3 - blades, e.self);


elseif ( blades < 5 ) then



SpawnBlades(1, e.self);

end
