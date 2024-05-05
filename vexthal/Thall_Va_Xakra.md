# Thall Va Xakra



[Thall Va Xakra](/npc/158136) is a level 60 Shade Warrior that spawns in [Vex Thal](/zone/158).

local NORTH_TVX_TYPE = 158136;
local SOUTH_TVX_TYPE = 158465;
local NORTH_VA_XAKRA1_SPAWNID = 365859;
local NORTH_VA_XAKRA2_SPAWNID = 365582;
local SOUTH_VA_XAKRA1_SPAWNID = 366962;
local SOUTH_VA_XAKRA2_SPAWNID = 366429;

local LINK_HATE_CAP = 5000;

local BAD_COORDS = {



{ -270, -157,



  -1000, -181,



  -1000, 1000,



},



{ -270, 573,



  -1000, -603,



  -1000, 1000,



},



{ -270, -157,



  181, 1000,



  -1000, 1000,



},



{ -270, 573,



  603, 1000,



  -1000, 1000,



},



{ -500, 1000,



  -1000, 1000,



  100, 1000,



},
};

function BadAreaCheck(self)


local hl = self:GetHateList();

local clients = {};

for ent in hl.entries do


if ( ent.ent:IsClient() ) then



table.insert(clients, ent.ent:CastToClient());




if ( self:GetX() > -260 and self:GetZ() < 0 ) then


self:GMMove(self:GetSpawnPointX(), self:GetSpawnPointY(), self:GetSpawnPointZ(), self:GetSpawnPointH());


self:WipeHateList();


for _, client in ipairs(clients) do


if ( not client:GetGM() ) then



for _, coords in ipairs(BAD_COORDS) do








if ( client:GetX() > coords[1] and client:GetX() < coords[2]





and client:GetY() > coords[3] and client:GetY() < coords[4]





and client:GetZ() > coords[5] and client:GetZ() < coords[6]




) then





**Signaled to:**  [Stop Cheating](/npc/158480)





return;






end

function AggroLink(boss, guardId)

local npcList = eq.get_entity_list():GetNPCList();

local bossTopHater = boss:GetHateTop();

local bossTopHate = boss:GetHateAmount(bossTopHater, false);

local cappedHate = bossTopHate;

local topHaterGuardHate;

if ( bossTopHate > LINK_HATE_CAP ) then


cappedHate = LINK_HATE_CAP;



if ( npcList ) then




for npc in npcList.entries do




if ( npc.valid and npc:GetSpawnPointID() == guardId ) then









if ( bossTopHater ) then





topHaterGuardHate = npc:GetHateAmount(bossTopHater, false);











if ( topHaterGuardHate < cappedHate ) then






npc:SetHate(bossTopHater, cappedHate);















return;






## Combat

if  Thall Va Xakra enters combat  then


**Set a timer** named *aggrocheck* for 1 seconds








if ( e.self:GetX() > -260 ) then



**Set a timer** named *cheat_check* for 1 seconds



BadAreaCheck(e.self);


else



**Stop timer** named *aggrocheck*


**Stop timer** named *cheat_check*


if ( e.self:GetX() < -150 ) then



e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());

end



## Timer(s)

if ( e.timer == "aggrocheck" ) then


local selfId = e.self:GetNPCTypeID();


local mob;



if ( selfId == NORTH_TVX_TYPE ) then



AggroLink(e.self, NORTH_VA_XAKRA1_SPAWNID);



AggroLink(e.self, NORTH_VA_XAKRA2_SPAWNID);


elseif ( selfId == SOUTH_TVX_TYPE ) then



AggroLink(e.self, SOUTH_VA_XAKRA1_SPAWNID);



AggroLink(e.self, SOUTH_VA_XAKRA2_SPAWNID);





elseif ( e.timer == "cheat_check" ) then


if ( e.self:GetX() > -260 and e.self:GetHPRatio() > 95 ) then



BadAreaCheck(e.self);


else



eq.stop_timer(e.timer);


end
