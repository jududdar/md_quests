# Guardian of Dresolik



[Guardian of Dresolik](/npc/212046) is a level 68 Giant Warrior that spawns in [Tower of Solusek Ro](/zone/212).

local GUARDIAN_SPAWNIDS = { 367793, 367794, 367795, 367796 };



## On NPC Spawn

local elist = eq.get_entity_list();

for _, id in ipairs(GUARDIAN_SPAWNIDS) do


elist:GetSpawnByID(id):SetTimer(1);
end



## On NPC Death

if ( not **spawned NPC:**  [Guardian of Dresolik](/npc/212046) ) then 


**Spawn NPC:**  [The Protector of Dresolik](/npc/212408) at (**y:** 1584, **x:** 606)
end



## Timer(s)


if ( e.timer == "bounds" ) then




if ( e.self:GetX() > 978 or e.self:GetX() < 558 ) then






e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());



**Guardian of Dresolik** clears hate list.



**Guardian of Dresolik casts:** [Annul Self](/spell/2830) on themselves.







end



## Combat

if  Guardian of Dresolik enters combat  then


**Set a timer** named *bounds* for 6 seconds

else


**Stop timer** named *bounds*
end
