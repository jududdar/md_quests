# Seilaen
local DEYID_TYPE = 204461; 

local ports = 0;

function MoveGroup(client, dist, x, y, z, h)

local group = client:GetGroup();

local raid = client:GetRaid();

local moved = 0;


if ( group and group:GroupCount() > 0 ) then


for i = 0, 5 do



local member = group:GetMember(i):CastToClient();




if ( member.valid ) then




if ( member:CalculateDistance(client:GetX(), client:GetY(), client:GetZ()) < dist ) then





member:MovePC(204, x, y, z, h*2);





moved = moved + 1;





if ( member:GetPet().valid and not member:GetPet():Charmed() ) then






member:GetPet():GMMove(x, y, z, 0);












return moved;

elseif ( raid and raid.valid ) then


local raidGroupID = raid:GetGroup(client:GetName());


local member;


for i = 0, 71 do



member = raid:GetMember(i);







if ( member and member.valid and raid:GetGroup(member:GetName()) == raidGroupID ) then








if ( member:CalculateDistance(client:GetX(), client:GetY(), client:GetZ()) < dist ) then





member:MovePC(204, x, y, z, h*2);





moved = moved + 1;





if ( member:GetPet().valid and not member:GetPet():Charmed() ) then






member:GetPet():GMMove(x, y, z, 0);














return moved;

else


client:MovePC(204, x, y, z, h*2);


if ( client:GetPet().valid and not client:GetPet():Charmed() ) then



client:GetPet():GMMove(x, y, z, 0);



return 1;

return 0;
function ClientOnPlateau()

local clientList = eq.get_entity_list():GetClientList();


if ( clientList ) then


for client in clientList.entries do






if ( not client:GetGM()




and client:GetY() > 800 and client:GetY() < 1365




and client:GetX() > 670 and client:GetX() < 1270




and client:GetZ() > 250



) then








return true;




return false;


## Dialog



**You say:** `hail`



>*Seilaen Seilaen looks at you with eyes wide with fear.  'Who.. who are you?  You.. You must help me!'*




**You say:** `help`



>**Seilaen says:** The forest, it.. I can feel it looking at me.. following me!  Oh, I just want to leave and go!



**You say:** `following`



>**Seilaen says:** I don't know what it could be, I was just walking home and.. and.. this doesn't look like the forest near my home at all!   Oh, and I am wearing my mother's Locket of Escape.. but it won't work for me!




**You say:** `locket`



>**Seilaen says:** My mother always carried this with her.  I have no idea why I suddenly have it.  Perhaps I can make it work for you, if you want me to?



**You say:** `want`





if ( not eq.get_entity_list():IsMobSpawnedByNpcTypeID(DEYID_TYPE) ) then



>**Seilaen says:** Oh it worked!  Are you still here?  Oh, please, don't have left me.  Come tell me you are still here!



eq.spawn2(DEYID_TYPE, 0, 0, 1011, 1081, 283.462, 59);



e.other:MovePC(204, 1213, 1103, 282, 187*2);


else



>**Seilaen says:** Hmm.. It doesn't seem to want to work.  Do you see Deyid?





**You say:** `where`



>**Seilaen says:** What did you see?




**You say:** `deyid`



>**Seilaen says:** Ohh, that must be what is causing all this trouble!  You all seem so brave.  Maybe if you chop down Deyid the Twisted I will be able to go home?  Will you please?  If you have gathered together and are prepared, have your leaders step forward and tell me their readiness.  Mother's Locket doesn't seem as bright as it was before.  I fear I can only use it but a couple more times.


**You say:** `ready`





if ( ports < 2 ) then







ports = ports + 1;



MoveGroup(e.other, 150, 1213, 1103, 282, 187);


else



>**Seilaen says:** Oh, I am sorry I can't make it work any more!  I do hope those that are up on the plateau will be sufficient to overcome the big tree!


end



## Signals

if ( e.signal == 1 ) then


**Seilaen shouts:** <span class="text-danger">Oh thank you! Thank you! I don't feel the trees watching me anymore!  And.. Let me try Mother's Locket again, I think it might work..</span>


**Seilaen despawns.**




elseif ( e.signal == 2 ) then


if ( not ClientOnPlateau() ) then



ports = 0;



eq.debug("Deyid event reset", 1);


else



**Set a timer** named *checkplateau* for 600 seconds

end



## On NPC Spawn

ports = 0;


## Timer(s)

if ( e.timer == "checkplateau" ) then


if ( not ClientOnPlateau() ) then



ports = 0;



**Stop timer** named *checkplateau*



eq.debug("Deyid event reset", 1);

end
