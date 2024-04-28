# Glykus Helmir
local BOAR_SPAWNIDS = { 361349, 361350, 361351, 361352, 361356 };
local FLEDGLING_TYPE = 214040; 
local ENRAGED_TYPE = 214308; 
local FIERCE_TYPE = 214296; 
local GREATER_TYPE = 214300; 
local ENCHANTED_TYPE = 214307; 

local boars = {};
for _, id in ipairs(BOAR_SPAWNIDS) do

boars[id] = 0;
function EvolveBoar(spawnId)


local entityId = boars[spawnId];



if ( entityId and entityId > 0 ) then




local mob = eq.get_entity_list():GetMobID(entityId);





if ( mob and mob.valid ) then






local typeId = mob:GetNPCTypeID();



local newType;







if ( typeId == FLEDGLING_TYPE ) then




newType = ENRAGED_TYPE;



elseif ( typeId == ENRAGED_TYPE ) then




newType = FIERCE_TYPE;



elseif ( typeId == FIERCE_TYPE ) then




newType = GREATER_TYPE;



elseif ( typeId == GREATER_TYPE ) then




newType = ENCHANTED_TYPE;









if ( newType ) then




local newMob = eq.spawn2(newType, 0, 0, mob:GetX(), mob:GetY(), mob:GetZ(), mob:GetHeading());




boars[spawnId] = newMob:GetID();




newMob:SetRunning(true);




mob:Depop();



end

function GetBoarIDs()

local npc;

local elist = eq.get_entity_list();



for _, id in ipairs(BOAR_SPAWNIDS) do




npc = elist:GetSpawnByID(id):GetNPC();


if ( npc.valid ) then



boars[id] = npc:GetID(); 

end

function DepopBoars()

eq.debug("Boar depop");



local npcList = eq.get_entity_list():GetNPCList();

local typeId;



for npc in npcList.entries do




if ( npc.valid ) then



typeId = npc:GetNPCTypeID()



if ( typeId == ENRAGED_TYPE or typeId == FIERCE_TYPE




or typeId == GREATER_TYPE or typeId == ENCHANTED_TYPE



) then




if ( npc:GetHP() > 0 ) then 





npc:Depop();






end

## Combat

if  Glykus Helmir enters combat  then



GetBoarIDs();


**Set a timer** named *evolve* for 59 seconds


**Set a timer** named *respawn* for 6 seconds


**Zone Wide Emote:** <span class="text-warning">*Glykus Helmir blows a carved boar horn. 'My pets! I enfuse you with the power of Zek.  Grow and battle with Glykus!'*</span>

else


**Stop timer** named *respawn*


**Set a timer** named *poof* for 90 seconds
end

## Timer(s)


if ( e.timer == "evolve" ) then



eq.debug("Evolving boars");





local elist = eq.get_entity_list();


local spawn, mob;



for spawnId, entityId in pairs(boars) do






spawn = elist:GetSpawnByID(spawnId);











if ( not spawn:GetNPC().valid ) then




spawn:SetTimer(1200000);













if ( entityId > 0 ) then




mob = elist:GetMobID(entityId);









if ( mob and mob.valid ) then





EvolveBoar(spawnId);









local npcList = eq.get_entity_list():GetNPCList();


local typeId;





for npc in npcList.entries do






if ( npc.valid ) then




typeId = npc:GetNPCTypeID()




if ( typeId == FLEDGLING_TYPE or typeId == ENRAGED_TYPE or typeId == FIERCE_TYPE





or typeId == GREATER_TYPE or typeId == ENCHANTED_TYPE




) then





npc:MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), -1, true);











if ( not e.self:IsEngaged() ) then



eq.stop_timer(e.timer);





elseif ( e.timer == "respawn" ) then







local elist = eq.get_entity_list();





for spawnId, entityId in pairs(boars) do






spawn = elist:GetSpawnByID(spawnId);







if ( entityId > 0 ) then




mob = elist:GetMobID(entityId);









if ( not mob or not mob.valid ) then





spawn:SetTimer(1);





boars[spawnId] = 0;






else




spawn:SetTimer(1);







elseif ( e.timer == "poof" ) then


eq.stop_timer(e.timer);





if ( not e.self:IsEngaged() ) then



DepopBoars();

end

## Signals

if ( e.signal == 1 ) then


GetBoarIDs(); 
end

## On NPC Death

DepopBoars();