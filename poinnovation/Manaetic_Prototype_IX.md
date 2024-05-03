# Manaetic Prototype IX


## Timer(s)


if ( e.timer == "teleport" ) then




eq.set_timer("teleport", math.random(2, 30) * 1000);


local target = e.self:GetTarget();





if ( target and target.valid ) then



e.self:SetHate(target, 1);



if ( target:IsClient() ) then




target:CastToClient():MovePC(206, 281, -239, 2, 64*2);







elseif ( e.timer == "boundscheck" ) then


if ( e.self:GetY() > -350 or e.self:GetY() < -600 ) then



>*Manaetic Prototype IX rattles violently and disappears!*



e.self:GMMove(e.self:CastToNPC():GetSpawnPointX(), e.self:CastToNPC():GetSpawnPointY(), e.self:CastToNPC():GetSpawnPointZ(), e.self:CastToNPC():GetSpawnPointH());



**Manaetic Prototype IX casts:** [Balance of the Nameless](/spell/3230) on themselves.



**Manaetic Prototype IX** clears hate list.



e.self:Heal();

end



## Combat

if  Manaetic Prototype IX enters combat  then


eq.set_timer("teleport", math.random(2, 30) * 1000);


**Set a timer** named *boundscheck* for 3 seconds

else


**Stop timer** named *teleport*


**Stop timer** named *boundscheck*
end
