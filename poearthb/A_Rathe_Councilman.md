# A Rathe Councilman



[A Rathe Councilman](/npc/222003) is a level 68 The Rathe Warrior that spawns in [Plane of Earth](/zone/222).

local MEZABLE_TYPE = 222003;
local UNMEZABLE_TYPE = 222039;
local SPAWNIDS = { 369377, 369380, 369382, 369384, 369386, 369387, 369376, 369378, 369379, 369381, 369383, 369385 };
local BOSS_TYPES = { 222035, 222037, 222036, 222038, 222008, 222009, 222010 }; 
local TELEPORT_BOUNDS = {

{ n = 957, s = 861, w = 2248, e = 1925 },

{ n = 564, s = 238, w = 2600, e = 2521 },

{ n = 569, s = 236, w = 1595, e = 1511 },

{ n = -55, s = -132, w = 2180, e = 1855 },
};
local THRESHOLDS = { 75, 50, 25, 11 };
local MIN_HITS = { 623, 533, 444, 354, 185 };
local MAX_HITS = { 2964, 2498, 2032, 1566, 850 };

local killed = {};
local state = {};

function TeleportClient(c)

local x = math.random(1, 4);

local rollX, rollY;



rollX = math.random(TELEPORT_BOUNDS[x].e, TELEPORT_BOUNDS[x].w);

rollY = math.random(TELEPORT_BOUNDS[x].s, TELEPORT_BOUNDS[x].n);



c:MovePC(222, rollX, rollY, -255, math.random(0, 510));



## On NPC Spawn

local elist = eq.get_entity_list();



local mySpawnID = e.self:GetSpawnPointID();

killed[mySpawnID] = nil;

state[mySpawnID] = nil;


for _, id in ipairs(SPAWNIDS) do


if ( id ~= mySpawnID ) then



if ( elist:GetSpawnByID(id):GetNPC().valid ) then




return;






for _, id in ipairs(SPAWNIDS) do


eq.update_spawn_timer(id, 1);

eq.debug("Full council repop");


## Combat

if  A Rathe Councilman enters combat  then


**Set a timer** named *teleport* for 60 seconds


if ( e.self:GetNPCTypeID() == MEZABLE_TYPE ) then



**Set a timer** named *check_mez* for 1 seconds


else



**Set a timer** named *checkhp* for 3 seconds


else


**Stop timer** named *teleport*


**Stop timer** named *check_mez*


**Stop timer** named *check_unmez*


**Stop timer** named *ten_min*
end



## Timer(s)


if ( e.timer == "checkhp" ) then




local mySpawnID = e.self:GetSpawnPointID();


local myState = state[mySpawnID] or 1;


local ratio = e.self:GetHPRatio();





if ( not e.self:IsEngaged() ) then







if ( myState > 1 and ratio > THRESHOLDS[1] ) then




state[mySpawnID] = 1;




e.self:ModifyNPCStat("min_hit", tostring(MIN_HITS[1]));




e.self:ModifyNPCStat("max_hit", tostring(MAX_HITS[1]));




e.self:ModifyNPCStat("accuracy", tostring(350));




e.self:ModifyNPCStat("atk", tostring(30));




eq.stop_timer(e.timer);




eq.debug("Councilman combat stats reset", 3);




return;







elseif ( myState == 1 and ratio > THRESHOLDS[1] ) then




eq.stop_timer(e.timer);








if ( myState > #THRESHOLDS ) then



return;


elseif ( ratio < THRESHOLDS[myState] ) then














local elist = eq.get_entity_list();



for _, id in ipairs(BOSS_TYPES) do




if ( elist:IsMobSpawnedByNpcTypeID(id) ) then





return;








]]











if ( eq.get_entity_list():GetSpawnByID(369490):GetNPC().valid ) then




return;








myState = myState + 1;



state[mySpawnID] = myState;



e.self:ModifyNPCStat("min_hit", tostring(MIN_HITS[myState]));



e.self:ModifyNPCStat("max_hit", tostring(MAX_HITS[myState]));



if ( myState == 5 ) then




e.self:ModifyNPCStat("accuracy", tostring(0));




e.self:ModifyNPCStat("atk", tostring(0));









if ( e.self:GetTarget().valid and e.self:GetTarget():IsClient() ) then





eq.debug( string.format("PoEarthB Rathe Councilman disempowered; Tank: %s <%s>", e.self:GetTarget():GetName(), e.self:GetTarget():CastToClient():GetGuildName()) );








**Zone Wide Emote:** <span class="text-warning">*The ground shudders beneath your feet as flecks of dirt and stone fall away from one of the Rathe.*</span>








elseif ( e.timer == "teleport" ) then





if ( e.self:IsMezzed() or e.self:GetHPRatio() < 11 ) then



return;






local hl = e.self:GetHateList();


local clients = {};


for ent in hl.entries do



if ( ent.ent:IsClient() and e.self:CalculateDistance(ent.ent:GetX(), ent.ent:GetY(), ent.ent:GetZ()) < 600 ) then




table.insert(clients, ent.ent:CastToClient());








if ( #clients > 0 ) then



TeleportClient( clients[math.random(1, #clients)] );



]]


local c = e.self:GetHateRandomClient(600);


if ( c and c.valid ) then



TeleportClient(c);





elseif ( e.timer == "ten_min" ) then







if ( e.self:IsMezzed() ) then



**A Rathe Councilman** clears hate list.



eq.debug("Mezzed Councilman hate list wiped", 3);


else



eq.stop_timer(e.timer);





elseif ( e.timer == "check_mez" ) then




if ( e.self:IsMezzed() ) then



eq.stop_timer(e.timer);



**Set a timer** named *ten_min* for 600 seconds



**Set a timer** named *check_unmez* for 1 seconds





elseif ( e.timer == "check_unmez" ) then




if ( not e.self:IsMezzed() ) then



eq.stop_timer(e.timer);



**Stop timer** named *ten_min*



**Set a timer** named *check_mez* for 1 seconds

end



## Signals

killed[e.signal] = 1;


## On NPC Death




local mySpawnID = e.self:GetSpawnPointID();

killed[mySpawnID] = 1;

local myType = e.self:GetNPCTypeID();





if ( myType == UNMEZABLE_TYPE ) then


eq.signal(MEZABLE_TYPE, mySpawnID);

else


eq.signal(UNMEZABLE_TYPE, mySpawnID);


for _, id in ipairs(SPAWNIDS) do


if ( not killed[id] ) then



return;



local elist = eq.get_entity_list();

if ( not elist:IsMobSpawnedByNpcTypeID(MEZABLE_TYPE) and not elist:IsMobSpawnedByNpcTypeID(UNMEZABLE_TYPE) ) then




**Zone Wide Emote:** <span class="text-warning">*The last of the council falls to the ground all signs of life gone.  Suddenly twelve voices are heard chanting a mystical spell saying, 'Time comes and time passes for the stone is forever.  Now we call upon our collective power to defend our stronghold!'  The chanting then stops and a deep throated primal scream is heard as the power of twelve comes together as one.  The Avatar of Earth has been summoned to defend Ragrax.*</span>


**Spawn NPC:**  [\#Avatar of Earth](/npc/222040) at (**y:** 410, **x:** 2050)



local variance = math.random(1, 1440);


local t = (60 * 60 + variance) * 60; 


for i, id in ipairs(SPAWNIDS) do



eq.update_spawn_timer(id, t*1000);

end
