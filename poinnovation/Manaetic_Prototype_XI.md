# Manaetic Prototype XI


## Timer(s)


if ( e.timer == "teleport" ) then




eq.set_timer("teleport", math.random(2, 30) * 1000);


local target = e.self:GetTarget();





if ( target and target.valid ) then



e.self:SetHate(target, 1);



if ( target:IsClient() ) then




target:CastToClient():MovePC(206, -231, -241, 2, 192*2);







elseif ( e.timer == "boundscheck" ) then


if ( e.self:GetX() > 400 or e.self:GetX() < 100 ) then



>*Manaetic Prototype XI rattles violently and disappears!*



e.self:GMMove(e.self:CastToNPC():GetSpawnPointX(), e.self:CastToNPC():GetSpawnPointY(), e.self:CastToNPC():GetSpawnPointZ(), e.self:CastToNPC():GetSpawnPointH());



**Manaetic Prototype XI casts:** [Balance of the Nameless](/spell/3230) on themselves.



**Manaetic Prototype XI** clears hate list.



e.self:Heal();

end



## Combat

if  Manaetic Prototype XI enters combat  then


eq.set_timer("teleport", math.random(2, 30) * 1000);


**Set a timer** named *boundscheck* for 3 seconds

else


**Stop timer** named *teleport*


**Stop timer** named *boundscheck*
end
