# Sir Edwin Motte
## Dialog

**You say:** `hail`



>**Sir Edwin Motte says:** Greetings, Soandso! How lucky you are to encounter the greatness of the legendary Sir Edwin Motte, slayer of cyclopes, battler of beasts, crusher of creatures, masher of monsters, eradicator of evil and champion of the third annual dart championship of Freeport.
end

## Signals

if ( e.self:IsEngaged() ) then


return;


local turn, bard;



if(e.signal == 1) then


>**Sir Edwin Motte says:** What is it with all this political revelry. Let's here more jests!


turn = true;

elseif(e.signal == 2) then


>**Sir Edwin Motte says:** Haha!! I shall laugh because it is true. Forgive me, ogre friends.


turn = true;

elseif(e.signal == 3) then


>**Sir Edwin Motte says:** I say, that Sir Lucan is no man of nobility. So they say...


turn = true;

elseif(e.signal == 4) then


>**Sir Edwin Motte says:** I say!! I have fought side by side with the great Antonius bayle. He is a man of supreme virtue.


turn = true;

elseif(e.signal == 5) then


>**Sir Edwin Motte says:** Bloody right, you are! Those fellows can't keep down any grog.


turn = true;

elseif(e.signal == 7) then


>**Sir Edwin Motte says:** Bloody right!! Sir Lucan is no knight. He is nothing more than a mere warrior.


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