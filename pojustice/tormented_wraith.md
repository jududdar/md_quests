# tormented wraith



[tormented wraith](/npc/201055) is a level 44 Shade Warrior that spawns in [Plane of Justice](/zone/201).





## Dialog

if ( e.self:GetNPCTypeID() == 201055 ) then


>*tormented wraith glares at you and does not respond.*

else


>*tormented wraith wails, sending a chill throughout your bones.*
end



## On NPC Death


if ( e.self:GetNPCTypeID() == 201055 ) then


local spawnId = e.self:GetSpawnPointID();


local roll = math.random(0, 99);


local t;





if ( spawnId == 345579 ) then



t = 201336; 


elseif ( spawnId == 345591 ) then



t = 201440; 


elseif ( spawnId == 345592 ) then



t = 201441; 






if ( roll < 50 ) then



eq.get_entity_list():MessageClose(e.self, true, 100, 0, "As the shade receives a killing blow, its weakened form falls to the ground, idle and still.");



eq.unique_spawn(t,0,0,e.self:GetX(),e.self:GetY(),e.self:GetZ(),0); 


else



eq.get_entity_list():MessageClose(e.self, true, 100, 0, "As the shade receives a killing blow, its image wavers for a moment, weakened, then fades away, unable to maintain its form.");



end
