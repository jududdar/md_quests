# The Tribunal
local PREPARED_TEXT = {

"nods slightly.  'Very well.  When you are ready, you may begin the trial of lashing.  You must protect the victims from their tormentors.  Be wary of the scourge of honor - you cannot fight it directly.  You must find and destroy its life force to defeat it.  We shall judge the mark of your success.'",

"nods slightly.  'Very well.  When you are ready, you may begin the trial of execution.  The victim will perish should the hooded executioner reach him.  Its life willonly when all of the nemeses which accompany it also perish.  We shall judge the mark of your success.'",

"nods slightly.  'Very well.  When you are ready, you may begin the trial of stoning.  The archers will not cease their punishment until nothing else stands.  Do not let the prisoners take more than they can bear.  We shall judge the mark of your success.'",

"nods slightly.  'Very well.  When you are ready, you may begin the trial of torture.  Only when a wraith of agony dies will the prisoners feel any relief.  Take care to find and kill it quickly, lest their torment overcome them.  We shall judge the mark of your success.'",

"nods slightly.  'Very well.  When you are ready, you may begin the trial of hanging.  Act quickly to destroy the spirits of suffocation before their victims perish.  We shall judge the mark of your success.'",

"nods slightly.  'Very well.  When you are ready, you may begin the trial of flame.  You must endure the heat of the fire and be sure not to let its creatures reach the center.  We shall judge the mark of your success.'",
};
local TRIAL_TEXT = {

"Trial of Lashing",

"Trial of Execution",

"Trial of Stoning",

"Trial of Torture",

"Trial of Hanging",

"Trial of Flame",
};
local SPAWNPOINT_IDS = { [345327] = 1, [345328] = 2, [345329] = 3, [345330] = 4, [345331] = 5, [345332] = 6 };
local CONTROLLER_IDS = { 201512, 201511, 201513, 201514, 201515, 201510 };
local CONTROLLER_COORDS = {

{ 1308, -1045, -13.248 },

{ 119, -1197, 73.75 },

{ -204, -1099, 73.75 },

{ 818, -1096, 58.75 },

{ 416, -1193, 73.75 },

{ 850, -660, 55.75 },
};
local TELEPORT_COORDS = {

{ 1340, -1120, 2, 64 },

{ 195, -1050, 75, 128 },

{ -150, -1190, 75, 0 },

{ 726, -1119, 90, 64 },

{ 490, -1050, 75, 128 },

{ 880, -660, 56, 128 },
};
local TRIAL_BOUNDARIES = {


{ -1000, -1500, 1500, 1000 },

{ -1000, -1500, 350, 50 },

{ -1000, -1500, 10, -300 },

{ -950, -1500, 1000, 650 },

{ -1000, -1500, 650, 350 },

{ -600, -850, 1000, 750 },
};
local AGENT_TYPE = 201075; 

local trialsUnderway = {};

function FindMarks(client)

local marks = { 31796, 31842, 31844, 31845, 31846, 31960 };

local numFound = 0;

for k, v in pairs(marks) do


if ( client:HasItem(v) ) then



numFound = numFound + 1;


return numFound;
function MobInTrial(trialNum)

local mobList = eq.get_entity_list():GetMobList();


if ( mobList ) then


for mob in mobList.entries do



if ( mob.valid and mob:GetY() < TRIAL_BOUNDARIES[trialNum][1]




and mob:GetY() > TRIAL_BOUNDARIES[trialNum][2]




and mob:GetX() < TRIAL_BOUNDARIES[trialNum][3]




and mob:GetX() > TRIAL_BOUNDARIES[trialNum][4]



) then




if ( mob:IsClient() and not mob:CastToClient():GetGM() ) then





return true;







if ( mob:IsNPC() and not mob:IsPet() and mob:CastToNPC():GetNPCTypeID() ~= AGENT_TYPE and mob:GetRace() ~= 216 ) then 





return true;







return false;
function MoveCorpses(trialNum)

local corpseList = eq.get_entity_list():GetCorpseList();


if ( corpseList ) then


for corpse in corpseList.entries do



if ( corpse.valid and corpse:GetY() < TRIAL_BOUNDARIES[trialNum][1]




and corpse:GetY() > TRIAL_BOUNDARIES[trialNum][2]




and corpse:GetX() < TRIAL_BOUNDARIES[trialNum][3]




and corpse:GetX() > TRIAL_BOUNDARIES[trialNum][4]



) then




if ( corpse:IsPlayerCorpse() ) then





corpse:MoveToGraveyard();






end

function MoveGroup(zone, client, dist, x, y, z, h)

local group = client:GetGroup();

local raid = client:GetRaid();


if ( group and group:GroupCount() > 0 ) then


for i = 0, 5 do



local member = group:GetMember(i):CastToClient();




if ( member.valid ) then




if ( member:CalculateDistance(client:GetX(), client:GetY(), client:GetZ()) < dist ) then





member:MovePC(zone, x, y, z, h*2);





if ( member:GetPet().valid ) then






if ( member:GetPet():Charmed() ) then







member:GetPet():BuffFadeByEffect(22); 






else







member:GetPet():GMMove(x, y, z, 0);














eq.get_entity_list():RemoveFromHateLists(member);










elseif ( raid and raid.valid ) then


local raidGroupID = raid:GetGroup(client:GetName());


local member;


for i = 0, 71 do



member = raid:GetMember(i);







if ( member and member.valid and raid:GetGroup(member:GetName()) == raidGroupID ) then








if ( member:CalculateDistance(client:GetX(), client:GetY(), client:GetZ()) < dist ) then





member:MovePC(zone, x, y, z, h*2);





if ( member:GetPet().valid ) then






if ( member:GetPet():Charmed() ) then







member:GetPet():BuffFadeByEffect(22); 






else







member:GetPet():GMMove(x, y, z, 0);














eq.get_entity_list():RemoveFromHateLists(member);









else


client:MovePC(zone, x, y, z, h*2);





if ( client:GetPet().valid ) then



if ( client:GetPet():Charmed() ) then




client:GetPet():BuffFadeByEffect(22); 



else




client:GetPet():GMMove(x, y, z, 0);





eq.get_entity_list():RemoveFromHateLists(client);
end



## Signals

local trialNum = SPAWNPOINT_IDS[e.self:GetSpawnPointID()];



if ( e.signal == trialNum ) then


eq.set_timer("delay"..trialNum, 60000);


trialsUnderway[trialNum] = true;


eq.debug(TRIAL_TEXT[trialNum].." failed.  Accessible again in 60 seconds", 1);

elseif ( e.signal == (trialNum + 6) ) then


eq.set_timer("delay"..trialNum, 1800000);


trialsUnderway[trialNum] = true;


eq.debug(TRIAL_TEXT[trialNum].." success.  Accessible again in 30 minutes", 1);
end



## Timer(s)

if ( #e.timer == 6 ) then


eq.stop_timer(e.timer);


local num = tonumber(e.timer:sub(6, 6));


if ( num ) then



MoveCorpses(num);



trialsUnderway[num] = nil;



eq.debug(TRIAL_TEXT[num].." is now available", 1);

end



## Dialog

local qglobals = eq.get_qglobals(e.self, e.other);

local trialNum = SPAWNPOINT_IDS[e.self:GetSpawnPointID()];



**You say:** `hail`



>*The Tribunal  fixes you with a dark, piercing gaze.  'What do you want, mortal?'*


return;


**You say:** `mavuin`







if ( qglobals.mavuin ) then






if ( (qglobals.mavuin == "1" and FindMarks(e.other) > 0) or qglobals.mavuin == "2" ) then




**Message:** <span class="text-warning">*The Tribunal tells you, 'You have completed a trial - impressive for mortals.  You can tell Mavuin that we will hear his plea.  We will seek him out as time befits us.'*</span>




if ( qglobals.mavuin == "1" ) then





eq.set_global("mavuin", "2", 5, "F");







**Message:** <span class="text-warning">*You have received a character flag!*</span>




return;









if ( qglobals.mavuin == "1" ) then




**Message:** <span class="text-warning">*The Tribunal tells you, 'So, mortal, you wish us to allow a prisioner to plead his case?  What power do you think that you hold that we should field your interests?  You must prove yourself in one of our trials before we will consider hearing this plea.'*</span>








elseif ( qglobals.mavuin == "3" ) then




**Message:** <span class="text-warning">*The Tribunal tells you, 'Do not worry about Mavuin.  We are currently reviewing his case and his accusations of interference in the Pantheon's plans.'*</span>










**You say:** `prove`





>**The Tribunal says:** The trials of the Tribunal are no easy affair. They will severely test your might and skill. Are you prepared for such an ordeal?




**You say:** `prepared`



e.self:Emote(PREPARED_TEXT[trialNum]);




elseif (e.message:findi("ready to begin the "..TRIAL_TEXT[trialNum])) then




if ( trialsUnderway[trialNum] or MobInTrial(trialNum) ) then 



>**The Tribunal says:** That trial is already underway.  You must wait.


else



trialsUnderway[trialNum] = true;



>**The Tribunal says:** Then begin.







eq.spawn2(CONTROLLER_IDS[trialNum], 0, 0, CONTROLLER_COORDS[trialNum][1], CONTROLLER_COORDS[trialNum][2], CONTROLLER_COORDS[trialNum][3], 0);











MoveGroup(201, e.other, 50, TELEPORT_COORDS[trialNum][1], TELEPORT_COORDS[trialNum][2], TELEPORT_COORDS[trialNum][3], TELEPORT_COORDS[trialNum][4]);



eq.debug(TRIAL_TEXT[trialNum].." begun by "..e.other:GetCleanName(), 1);





**You say:** `knowledge`



local marks = FindMarks(e.other);





if ( qglobals.seventh or marks == 6 ) then



**Message:** <span class="text-warning">*The Tribunal tells you, 'Most impressive.  It has been long since a mortal has shown such prowess.'  It considers you for a long moment.  'There is one final test that you must undergo.'  A gleaming metal disc appears in your hand.  'Hold up the Mark of Justice as you enter the portal, and prepare for your judgement.'*</span>







if ( not qglobals.seventh ) then 




eq.set_global("seventh", "1", 5, "F");





**Message:** <span class="text-warning">*You have received a character flag!*</span>







if ( not **You possess item:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/31599" data-url="31599" class="tooltip-link link">The Mark of Justice</a> x 1




e.other:SummonItem( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/31599" data-url="31599" class="tooltip-link link">The Mark of Justice</a>); 




elseif ( marks > 0 ) then



**Message:** <span class="text-warning">*The Tribunal tells you, 'You have done well, mortal, but there are more trials yet for you to complete.'*</span>


else



**Message:** <span class="text-warning">*The Tribunal considers you for a long moment.  'The knowledge of the gods is not so easily given to an unproven mortal.'*</span>

end
