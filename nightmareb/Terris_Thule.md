# Terris Thule



[Terris Thule](/npc/204483) is a level 1 Terris Thule Warrior that spawns in [The Lair of Terris Thule](/zone/221).





local PLANAR_PROJECTION_TYPE = 221042;
local DEFILER_SMALL_TYPE = 221045;
local DEFILER_LARGE_TYPE = 221044;
local GARG_TYPE = 221043;
local GARG_SPAWN_IDS = { 365397, 366053, 366176, 367232 };



## On NPC Death

eq.spawn2(PLANAR_PROJECTION_TYPE, 0, 0, e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0);

eq.signal(PLANAR_PROJECTION_TYPE, e.killer:GetID()); 


## On NPC Spawn

eq.set_next_hp_event(95);
function SpawnDefilers(mob)

local numSpawns = 0;

local hateList = mob:GetHateList();



for ent in hateList.entries do


if ( ent.ent:IsClient() and ent.damage > 0 ) then



numSpawns = numSpawns + 1;



local t;

for i = 1, numSpawns do


t = math.random(1, 2);


if ( t == 1 ) then



t = DEFILER_SMALL_TYPE;


else



t = DEFILER_LARGE_TYPE;






eq.spawn2(t, 0, 0, -1661, -168, 140, 0); 
end

function event_hp(e)


if ( e.hp_event == 95 ) then


eq.get_entity_list():MessageClose(e.self, true, 250, 0, "The sound of a thousand terrified screams fills your head.  You feel yourself becoming a part of the fabric of this nightmare realm.");


eq.set_next_hp_event(79);




elseif ( e.hp_event == 79 ) then


eq.set_next_hp_event(69);


SpawnDefilers(e.self);



elseif ( e.hp_event == 69 ) then


eq.set_next_hp_event(50);


SpawnDefilers(e.self);



elseif ( e.hp_event == 50 ) then


eq.set_next_hp_event(40);


eq.get_entity_list():MessageClose(e.self, true, 250, 0, "As if in a waking nightmare, you feel your movements slow and your arms begin to fail you.  Each swing of your weapon feels as if it will miss its mark.   Even your legs begin to fail you, as you fall deeper into the dreamlike state!");


**Terris Thule casts:** [Direption of Dreams](/spell/3150) on themselves.



elseif ( e.hp_event == 40 ) then


**Terris Thule shouts:** <span class="text-danger">You will not escape my realm so easily!</span>


eq.get_entity_list():MessageClose(e.self, true, 250, 0, "The air grows thick with the smell of burning mana.  A rumbling sound draws your attention to the massive statues that rest above the ancient monoliths.  The statues begin to crumble, as they shift their attention from the heavens to you!");





local npcList = eq.get_entity_list():GetNPCList();





if ( npcList ) then






for npc in npcList.entries do





if ( npc.valid and npc:GetSpawnPointID() ) then










for _, id in ipairs(GARG_SPAWN_IDS) do






if ( id == npc:GetSpawnPointID() ) then







eq.spawn2(GARG_TYPE, 0, 0, npc:GetX(), npc:GetY(), npc:GetZ(), npc:GetHeading());







npc:Depop(true);








break;
















end



## Combat

if  Terris Thule enters combat  then


**Set a timer** named *boundscheck* for 1 seconds

else


**Set a timer** named *checkhp* for 3 seconds


**Stop timer** named *boundscheck*
end



## Timer(s)


if ( e.timer == "checkhp" ) then




if ( e.self:GetHPRatio() == 100 ) then



**Stop timer** named *checkhp*



eq.set_next_hp_event(95);















local elist = eq.get_entity_list();







for _, id in ipairs(GARG_SPAWN_IDS) do




elist:GetSpawnByID(id):SetTimer(1);





eq.depop_all(GARG_TYPE);



]]





elseif ( e.timer == "boundscheck" ) then




if ( e.self:GetX() > -1580 or e.self:GetX() < -2090 or e.self:GetY() > 250 or e.self:GetY() < -280 ) then



eq.get_entity_list():MessageClose(e.self, true, 200, 0, "Terris Thule disappears into the ether and reforms at the center of her chamber, cleansed of your magic!");



e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());



**Terris Thule casts:** [Balance of the Nameless](/spell/3230) on themselves.

end
