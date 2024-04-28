# player
function event_click_door(e)

local id = e.door:GetDoorID();


if ( id >= 14 and id <= 17 ) then






local elist = eq.get_entity_list();


if ( e.self:GetGM()



or elist:IsMobSpawnedByNpcTypeID(214311)




or elist:IsMobSpawnedByNpcTypeID(214312)




or elist:IsMobSpawnedByNpcTypeID(214313)




or elist:IsMobSpawnedByNpcTypeID(214320)



) then



e.door:ForceOpen(e.self);





elseif ( id == 2 or id == 3 ) then





if ( not **spawned NPC:**  [Vallon Zek](/npc/214316)



and not **spawned NPC:**  [Vallon Zek](/npc/214317)


) then






e.self:MovePC(214, 279, 182, 5, 128*2);



if ( e.self:GetPet().valid and not e.self:GetPet():Charmed() ) then




e.self:GetPet():GMMove(279, 182, 5, 128*2);




else



e.self:Message(0, "The doors are held shut by magical forces.");




elseif ( id == 4 or id == 5 ) then





if ( not **spawned NPC:**  [Tallon Zek](/npc/214026) ) then






e.self:MovePC(214, 279, 182, 5, 128*2);



if ( e.self:GetPet().valid and not e.self:GetPet():Charmed() ) then




e.self:GetPet():GMMove(279, 182, 5, 128*2);




else



e.self:Message(0, "The doors are held shut by magical forces.");




elseif ( id == 24 ) then






local rz = eq.get_entity_list():GetMobByNpcTypeID(214312);



if ( rz and rz.valid and rz:IsEngaged() ) then



e.self:MovePC(214, rz:GetX(), rz:GetY(), rz:GetZ(), rz:GetHeading());



return;




e.self:MovePC(203, -4, -191, -628, 149);





elseif ( id == 25 and not **spawned NPC:**  [Glykus Helmir](/npc/214053) ) then



e.self:MovePC(203, -4, -191, -628, 149);





elseif ( id == 26 and not **spawned NPC:**  [Tagrin Maldric](/npc/214054) ) then



e.self:MovePC(203, -4, -191, -628, 149);

end