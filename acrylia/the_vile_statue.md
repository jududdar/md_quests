# the vile statue







## On NPC Spawn

eq.set_proximity(-61, -20, -797, -761, -15, 0);
function event_enter(e)

if ( e.other:GetGM() ) then


return


**Set a timer** named *cast* for 2 seconds
function event_leave(e)

**Stop timer** named *cast*


## Timer(s)


if ( e.timer == "cast" ) then





local clientList = eq.get_entity_list():GetClientList();


local clients;



if ( clientList ) then



for client in clientList.entries do








if ( not client:GetGM() and client:GetZ() > -15 and client:GetZ() < 0





and client:GetY() > -797 and client:GetY() < -761





and client:GetX() > -61 and client:GetX() < -20




) then










clients = true;





e.self:CastSpell(2858, client:GetID(), 0, 1); 









if ( not clients) then



**Stop timer** named *cast*

end
