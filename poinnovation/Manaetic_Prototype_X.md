# Manaetic Prototype X


## Timer(s)


if ( e.timer == "teleport" ) then




eq.set_timer("teleport", math.random(2, 30) * 1000);


local target = e.self:GetTarget();





if ( target and target.valid ) then



e.self:SetHate(target, 1);



if ( target:IsClient() ) then




target:CastToClient():MovePC(206, 1, -473, 2, 128*2);







elseif ( e.timer == "boundscheck" ) then


if ( e.self:GetX() > -100 or e.self:GetX() < -400 ) then



>*Manaetic Prototype X rattles violently and disappears!*



e.self:GMMove(e.self:CastToNPC():GetSpawnPointX(), e.self:CastToNPC():GetSpawnPointY(), e.self:CastToNPC():GetSpawnPointZ(), e.self:CastToNPC():GetSpawnPointH());



**Manaetic Prototype X casts:** [Balance of the Nameless](/spell/3230) on themselves.



**Manaetic Prototype X** clears hate list.



e.self:Heal();

end



## Combat

if  Manaetic Prototype X enters combat  then


eq.set_timer("teleport", math.random(2, 30) * 1000);


**Set a timer** named *boundscheck* for 3 seconds

else


**Stop timer** named *teleport*


**Stop timer** named *boundscheck*
end
