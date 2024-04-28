# Maareq the Prophet
local power = 0;
local state = 0;

## On NPC Spawn

power = 0;

state = 0;
## Combat

if  Maareq the Prophet enters combat  then


**Set a timer** named *minion* for 5 seconds


**Stop timer** named *revert*

else


**Stop timer** named *minion*


**Stop timer** named *upgrade*


if ( state > 0 ) then



**Set a timer** named *revert* for 480 seconds

end

## Timer(s)


if ( e.timer == "minion" ) then




local mob = **Spawn NPC:**  [a minion of Maareq](/npc/207297) at (**y:** 0, **x:** -25)




mob:CastToNPC():MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0, true);











if ( e.self:GetZ() < 440 or e.self:GetZ() > 475 ) then



e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());



**Maareq the Prophet casts:** [Balance of the Nameless](/spell/3230) on themselves.



]]



elseif ( e.timer == "upgrade" ) then


eq.stop_timer(e.timer);





if ( state == 0 ) then



>*Maareq the Prophet raises his arms towards the sky and screams! His exposed skin bulges and writhes, as the creatures that clung to him move beneath its surface.*



>*Maareq the Prophet shouts 'My prophecy was fulfilled for Saryrn.  Your fate shall come to fruition as well!  I have a special vision for you.  Now, step forward like the obedient cattle you are.  Let us begin this harvest of pain!'*




e.self:ModifyNPCStat("special_abilities", "5,1,25"); 



e.self:ChangeSize(12);






elseif ( state == 1 ) then



>**Maareq the Prophet says:** Your assault only prolongs the inevitable!  I can feel the fear dripping for you.  Give into it.  Give up while you still have enough energy to suffer properly!



eq.get_entity_list():MessageClose(e.self, true, 200, 0, "A horrific roar reverberates throughout the zone!  Every surface shakes violently for a moment as the sound rolls past you!");




e.self:SetTexture(0);



e.self:SetRace(281);



e.self:SetGender(2);



e.self:ChangeSize(12);



e.self:ModifyNPCStat("special_abilities", "5,0,0"); 



e.self:ModifyNPCStat("special_abilities", "4,1,10"); 





elseif ( state == 2 ) then



>*Maareq the Prophet radiates with rage!  The ferocity of it's attacks increases dramatically as it's skin begins to bubble and burst in places!*



e.self:ChangeSize(17);



e.self:ModifyNPCStat("attack_delay", "8");



state = state + 1;




elseif ( e.timer == "revert" ) then


eq.stop_timer(e.timer);





e.self:SetTexture(16);


e.self:SetRace(1);


e.self:SetGender(0);


e.self:ChangeSize(7);


e.self:ModifyNPCStat("special_abilities", "5,0,0"); 


e.self:ModifyNPCStat("special_abilities", "4,0,0"); 


e.self:ModifyNPCStat("attack_delay", "12");


power = 0;


state = 0;
end

## Signals

if ( e.signal == 1 ) then


power = power + 1;



if ( (state < 3 and power >= 40) or (state < 2 and power >=20) or (state == 0 and power >= 10) ) then



**Set a timer** named *upgrade* for 3 seconds

end

## On NPC Death

**Despawn all instances of:**  [a minion of Maareq](/npc/207297)



local tylis = eq.get_entity_list():GetMobByNpcTypeID(207014); 

if ( tylis and tylis.valid ) then


tylis:SetBodyType(1, false);

end
