# Agnarr the Storm Lord
local KARANA_TYPE = 209136;
local JOLUR_TYPE = 209147; 
local EKIL_TYPE = 209142; 
local OLJIN_TYPE = 209148; 
local HIBDIN_TYPE = 209146; 

local ADD_TYPES = {

[JOLUR_TYPE] = 1,

[EKIL_TYPE] = 1,

[OLJIN_TYPE] = 1,

[HIBDIN_TYPE] = 1,

[209124] = 1, 

[209123] = 1, 

[209125] = 1, 

[209130] = 1, 
};

function SpawnGiant(id)

eq.unique_spawn(id, 0, 0, -1070, -1739, 2257, 64);
## Combat

if  Agnarr the Storm Lord enters combat  then


**Zone Wide Emote:** <span class="text-warning">*Agnarr the Storm Lord says 'Fool! This is the realm of the Storm Giants now, and you hope to defeat me here?'*</span>


**Set a timer** named *portals* for 120 seconds


**Set a timer** named *link* for 45 seconds


if ( e.self:GetHPRatio() > 96 ) then



eq.set_next_hp_event(75);



**Set a timer** named *spawn* for 3 seconds


else


**Stop timer** named *portals*


**Stop timer** named *link*
end

## Timer(s)


if ( e.timer == "link" ) then



if ( e.self:GetZ() < 2200 ) then



e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());




local npcList = eq.get_entity_list():GetNPCList();



for npc in npcList.entries do






if ( npc.valid and ADD_TYPES[npc:GetNPCTypeID()] and e.self:GetTarget() and e.self:GetTarget().valid ) then




npc:AddToHateList(e.self:GetTarget(), 100);









if ( npc:GetZ() < 2200 ) then





npc:GMMove(npc:GetSpawnPointX(), npc:GetSpawnPointY(), npc:GetSpawnPointZ(), 0);









elseif ( e.timer == "portals" ) then


**Zone Wide Emote:** <span class="text-warning">*Agnarr strikes his staff to the ground, causing great ripples of energy to rage across the room.*</span>


**Signaled to:**  [A storm portal](/npc/209034)





if ( e.self:GetHPRatio() < 25 ) then



**Set a timer** named *portals* for 60 seconds






elseif ( e.self:GetHPRatio() < 50 ) then



**Set a timer** named *portals* for 90 seconds





elseif ( e.timer == "spawn" ) then


eq.stop_timer(e.timer);


SpawnGiant(JOLUR_TYPE); 
end

function event_hp(e)


if ( e.hp_event == 75 ) then


eq.set_next_hp_event(50);


SpawnGiant(EKIL_TYPE); 




elseif ( e.hp_event == 50 ) then


eq.set_next_hp_event(25);


SpawnGiant(OLJIN_TYPE); 



elseif ( e.hp_event == 25 ) then


SpawnGiant(HIBDIN_TYPE); 

end

## On NPC Death

eq.spawn2(KARANA_TYPE, 0, 0, -477, -1758, 2355, 192);

eq.signal(KARANA_TYPE, e.killer:GetID()); 