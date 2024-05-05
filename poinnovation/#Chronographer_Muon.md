# Chronographer Muon



[Chronographer Muon](/npc/206044) is a level 70 Clockwork Golem Warrior that spawns in [Plane of Innovation](/zone/206).

local MAELIN_TYPE = 206209;

function HasItemInvOnly(client, itemid)




for i = 0, 30, 1 do


local thisitem = client:GetItemIDAt(i);


if(thisitem == itemid) then



return true;





for i = 250, 339, 1 do


local thisitem = client:GetItemIDAt(i);


if(thisitem == itemid) then



return true;

end



## Dialog


local qglobals = eq.get_qglobals(e.other);



if ( qglobals.zebuxoruk == "2" and HasItemInvOnly(e.other, 29165) ) then 




**You say:** `hail`




**Message:** <span class="text-warning">*Chronographer Muon tells you, 'Acquisition of power completed.  Would you like to be transported to the time-projection chamber?'*</span>






**You say:** `yes`




**Message:** <span class="text-warning">*Chronographer Muon tells you, 'Compliance.'*</span>



e.other:MovePC(206, 291, -860, -1850, 64*2);



eq.unique_spawn(MAELIN_TYPE, 0, 0, 763, -837, -1887.122, 184);


else




**You say:** `hail`




**Message:** <span class="text-warning">*Chronographer Muon tells you, 'Greeting acknowledged.  I have no use for you at this time.  Good bye.'*</span>

end
