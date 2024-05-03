# Biggle Limbokker


## Dialog

**You say:** `hail`



>**Biggle Limbokker says:** Good day to you, Soandso! Learn to mind your own business in this place. If a fight breaks out, do not get in the way.
end



## Signals

if ( e.self:IsEngaged() ) then


return;


local turn, bard;



if ( e.signal == 1 ) then


>**Biggle Limbokker says:** Yes! Send more high elf ladies to Freeport.


turn = true;

elseif ( e.signal == 4 ) then


>**Biggle Limbokker says:** Qeynos is a great city. Their troops have aided Rivervale many times.


turn = true;

elseif ( e.signal == 5 ) then


>**Biggle Limbokker says:** Those Erudites are no fun at all.


turn = true;

elseif ( e.signal == 6 ) then


>**Biggle Limbokker says:** That voice must have scared him away.


turn = true;

elseif ( e.signal == 7 ) then


>**Biggle Limbokker says:** Biggle Limbokker for ruler of Qeynos!! A vote for Biggle is a vote for grub, grog and song.


turn = true;



if ( turn ) then


bard = eq.get_entity_list():GetMobByNpcTypeID(10141);





if ( not bard.valid ) then



bard = eq.get_entity_list():GetMobByNpcTypeID(10158);





if ( not bard.valid ) then 



bard = eq.get_entity_list():GetMobByNpcTypeID(10165);





if ( bard.valid ) then



e.self:FaceTarget(bard);

end
